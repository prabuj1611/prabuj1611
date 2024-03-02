graph LR
A[Customer Contact] --> B{Proposal Complete (20%)}
B --> C{All Info Included}
B --> D{Missing Information Identified}
C --> E{Confirm Customer Info}
C --> F{Verify Contact Info Accuracy}
C --> G{Log Request Details}
C --> H{Scientist/Technician Needed?}
D --> I{Impact Details Missing (40%)}
D --> J{Incorrect Data Provided (35%)}
D --> K{Other Missing Information (25%)}
I | J | K --> L{Request Clarification (Email/Callback)}
L --> M{Delays Work Progress}
M --> N{Prioritization}
E --> F --> G --> H --> N


