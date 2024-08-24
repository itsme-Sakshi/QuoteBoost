This project is a React application that generates and displays advisable/motivational quotes using the Advice Slip API. The application is containerized using Docker for easy deployment and portability.

Features
Real-time Quote Generation: Fetches and displays random motivational quotes with each refresh.
React-Based Frontend: Built with React to ensure a responsive and interactive user experience.
API Integration: Utilizes the Advice Slip API for fetching quotes.
Dockerized Application: Easily deployable using Docker, with a public Docker image available.

Setup:
- run ```npm i && npm start```

Running via docker:
- docker pull vsakshi/react-app
- docker run -p 3000:3000 vsakshi/react-app

