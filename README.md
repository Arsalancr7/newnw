          Brightfield (Ph3)
                 │
     ┌───────────┴───────────┐
     │                       │
Foreground (Object)     Background (Context)
     │                       │
     ▼                       ▼
  DMT Model              VAE Model
     │                       │
     ▼                       ▼
Predicted Object       Predicted Background
 (505, 555)              (505, 555)
     └───────────┬───────────┘
                 ▼
     Combine Foreground + Background
                 │
                 ▼
   Final Fluorescence Images (505, 555)
