real-Time Chat Application with Django Channels and React – This is a full-stack real-time chat app using Django Channels for the backend and React for the frontend.
It allows users to send and receive messages instantly in multiple chat rooms with WebSocket support for seamless bi-directional communication. Features include dynamic WebSocket URLs, auto-scroll to the latest message, and user-tagged messages. The backend stack includes Django,
Channels, Redis, and ASGI, while the frontend is built with React and WebSockets. To run the project, make sure Redis is installed and running, then set up the backend with pip install -r requirements.txt, 
run python manage.py migrate, and start the server using python manage.py runserver. For the frontend, navigate to the frontend folder, run npm install to install dependencies,
and start the React development server with npm start. Once running, access the app at http://localhost:3000 (React) or http://localhost:8000 (Django). This project demonstrates a scalable, 
real-time messaging solution with a modern web tech stack.
