## 0.6: New note in Single page app diagram.
sequenceDiagram

    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: 201 Created
    deactivate server

<img width="811" alt="Screenshot 2024-03-11 at 10 28 37 AM" src="https://github.com/Inesh-Reddy/part-0/assets/52624669/27d12203-785b-49d9-882f-e94efdae5df5">
