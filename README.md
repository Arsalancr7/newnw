flowchart TD
    A["Brightfield (Ph3)"] --> B1["Foreground (Object)"]
    A --> B2["Background (Context)"]

    B1 --> C1["DMT Model"]
    B2 --> C2["VAE Model"]

    C1 --> D1["Predicted Object (505, 555)"]
    C2 --> D2["Predicted Background (505, 555)"]

    D1 --> E["Combine Foreground + Background"]
    D2 --> E

    E --> F["Final Fluorescence Images (505, 555)"]



