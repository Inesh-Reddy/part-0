## 0.6: New note in Single page app diagram.
sequenceDiagram

    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: 201 Created
    deactivate server

![alt text](<Screenshot 2024-03-11 at 10.28.37 AM.png>)