Chatterly is a real-time chat application built using Flask and Flask-SocketIO.
It allows multiple users to connect, send messages instantly, and update their usernames dynamically.
Each user is assigned a random avatar and username when they join.

Features-:
🔹 Real-time messaging with WebSockets (Socket.IO)
🔹 Random unique username + avatar generated on join
🔹 User join/leave notifications
🔹 Ability to update username anytime
🔹 Avatars displayed next to chat messages
🔹 Modern UI with responsive design

Tech Stack-:
1. Backend: Python, Flask, Flask-SocketIO
2. Frontend: HTML, CSS, JavaScript
3. Realtime Engine: WebSockets (via Socket.IO)

How to Run Locally-:
1. Clone the repository:
git clone https://github.com/tejaskotekar04/Chatterly---Real-Time-Messaging-Web-App.git

cd Chatterly---Real-Time-Messaging-Web-App

2. Create and activate a virtual environment-:
   
   python -m venv venv

   .\venv\Scripts\activate    # Windows

    source venv/bin/activate   # macOS/Linux

3. Install dependencies-:
   pip install -r requirements.txt

4. Run the app-:
   
   python app.py

5. Open in browser-:
   
   http://127.0.0.1:5000/

6. Open in multiple tabs to test real-time chat.

 
