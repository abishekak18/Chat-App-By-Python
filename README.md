# Python Chat App

A real-time chat application built with **Socket.IO** and **Python**. This app supports private chat, username updates, and a clean, responsive UI.

## Live Demo
You can access the live version of the application [here](https://chat-app-by-python.onrender.com).

---

## Features

- **Real-time communication** using Socket.IO
- User-friendly and modern UI
- Update usernames dynamically
- Responsive design for all devices
- Handles multiple users in the chatroom
- Notifications for users joining or leaving the chat

---

## Technologies Used

- **Frontend**: HTML, CSS (custom design with variables and modern styles), JavaScript
- **Backend**: Python, Flask
- **WebSocket Library**: Socket.IO
- **Hosting**: Render

---

## Setup Instructions

Follow these steps to run the project locally:

### Prerequisites
- Install **Python** (version 3.8 or above)
- Install **Node.js** (for Socket.IO dependency)
- Install **pip** (Python package manager)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/abishekak18/chat-app.git
   cd chat-app
   ```

2. **Install Python Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Start the Server**
   Run the Python script to start the backend server:
   ```bash
   python app.py
   ```

4. **Access the App**
   Open a browser and navigate to:
   ```
   http://localhost:5000
   ```

---

## Folder Structure

```
chat-app/
├── templates/
│   ├── index.html
├── app.py
├── requirements.txt
└── README.md
```

---

## Deployment

This app is hosted on Render. To deploy the app yourself:
1. Create a free account on [Render](https://render.com).
2. Connect your GitHub repository.
3. Deploy the service as a **web service**.

---

## Contributing

Contributions are welcome! Here's how you can get started:
1. Fork the repository.
2. Create a new branch.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes.
   ```bash
   git commit -m "Add your message here"
   ```
4. Push the changes to your forked repository.
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---
