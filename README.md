# TangoTube - Ballroom Instructional Video Platform

TangoTube is a web application that allows users to explore and share dance videos. It offers a seamless dance video experience, from watching captivating performances to uploading your dance creations.

![image](https://github.com/jamesschroeder88/TangoTube/assets/85189796/5fb4a75a-6757-4d71-b78b-fe32e1d6cc34)


## Features

- **List Videos:** Discover a wide range of dance videos from various genres.
- **Watch a Video:** Enjoy high-quality video playback for an immersive viewing experience.
- **Sign In/Out:** Create an account or log in to access additional features.
- **Upload a Video:** Share your dance videos with the global dance community.
- **Watch Transcoded Video:** Experience smooth video playback with optimized transcoded content.

## Tech Stack

- TypeScript
- Next.js
- Express.js
- Docker
- FFmpeg
- Firebase Auth
- Firebase Functions
- Firebase Firestore
- Google Cloud Storage
- Google Cloud Pub/Sub
- Google Cloud Run

## Getting Started

![image](https://github.com/jamesschroeder88/TangoTube/assets/85189796/e2673cc0-b11b-4821-a5ba-3b204dcc0af9)
![image](https://github.com/jamesschroeder88/TangoTube/assets/85189796/341b5e6b-62b3-461d-9d3d-af4c1cc68e86)


To get TangoTube up and running on your local machine, follow these steps:

1. Clone this repository.
2. Install project dependencies with `npm install` or `yarn install`.
3. Configure your Firebase project and set up the necessary credentials.
4. Run the application locally with `npm run dev` or `yarn dev`.
5. View a demo here: [https://yt-web-client-pyceld7pfq-uc.a.run.app/](https://yt-web-client-pyceld7pfq-uc.a.run.app/)

## Architecture

TangoTube's architecture is designed for scalability and performance. Key components include:

- **Cloud Storage:** Stores user-uploaded videos.
- **Pub/Sub:** Facilitates communication for video processing.
- **Cloud Run (Video Processing):** Efficient video transcoding and upload service.
- **Cloud Firestore:** Stores video metadata.
- **Cloud Run (Web Client):** Hosts the Next.js web app.
- **Firebase Functions:** Backend logic for fetching and serving videos.
