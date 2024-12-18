# CodeTube

CodeTube is an open-source platform for sharing, discovering, and learning code snippets, tutorials, and projects. Inspired by the format of video-sharing platforms, CodeTube aims to bring developers together to collaborate, teach, and showcase their work.

## Features

- **Snippet Sharing**: Upload and share your code snippets with the world.
- **Code Playlists**: Group related snippets or tutorials into playlists.
- **Interactive Code Viewer**: View, edit, and run code snippets in the browser.
- **Community Interaction**: Like, comment, and share code snippets to foster collaboration.
- **Search and Discovery**: Find code snippets or playlists based on tags, programming languages, or topics.

## Tech Stack

- **Frontend**: React, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Code Execution**: Dockerized sandbox environments

## Installation

Follow these steps to set up CodeTube locally:

### Prerequisites

- Node.js (v16 or above)
- MongoDB (running locally or in the cloud)
- Docker (for code execution environments)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/codetube.git
   cd codetube
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGO_URI=your_mongo_db_uri
   JWT_SECRET=your_jwt_secret
   DOCKER_HOST=your_docker_host
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Access the application:
   Open your browser and navigate to `http://localhost:3000`.

## Contribution

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git add .
   git commit -m "Add your message here"
   git push origin feature-name
   ```
4. Open a pull request on the main repository.

## License

CodeTube is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions, suggestions, or feedback, please open an issue in the repository or contact us at support@codetube.dev.

---

Enjoy sharing and discovering code with **CodeTube**!
