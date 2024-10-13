

# Open Source Project Discovery 🌐

Open Source Project Discovery is a beginner-friendly platform designed to help aspiring developers and open-source enthusiasts discover interesting GitHub repositories to contribute to. Users can search, explore, and star repositories with ease.

## 🚀 Demo
- will be updated and developed soon and link will be updated here
- till then you can visit the video link [here](https://youtu.be/KDQmCNigCps?si=7mPueiQfDbocDwfa).
  ![alt text](<Screenshot (102).png>) 
  ![alt text](<Screenshot (103).png>) 
  ![alt text](<Screenshot (104).png>)
## ✨ Features

- **Explore Repositories**: Search and explore repositories by name, stars, forks, language, and more.
- **Star/Unstar Repositories**: Save repositories that you find interesting and star them directly from the platform.
- **Detailed Information**: View detailed information about each repository, including stars, forks, and programming language.
- **Beginner-Friendly**: Tailored for beginner developers looking to dive into open-source contributions.
- **User-Friendly Interface**: Simple, intuitive interface designed for easy exploration.

## 🛠️ Tools & Technologies

- **React**: Frontend framework for building the user interface.
- **Express.js**: Backend framework for handling API requests.
- **Node.js**: Runtime environment for executing JavaScript on the server.
- **MongoDB**: NoSQL database for storing repository data.
- **Axios**: For making HTTP requests to the backend.
- **GitHub API**: To fetch repository data from GitHub.

## 🛠️ Installation

### Prerequisites

- Node.js (v20 or higher)
- npm (v9 or higher)
- MongoDB

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Lakhwinderr/Open-Source-Discovery.git
   cd Open-Source-Discovery
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Set Up Environment Variables**

   Create a `.env` file in ./backend directory and configure the necessary variables for MongoDB connection and GitHub API access.
   ```
   GITHUB_TOKEN
   MONGODB_CONNECTION_STRING
   ```
4. **Start the Development Server**

   First make sure to start backend server
   ```
   cd backend
   node index.js
   ```
   Then go to main project folder and run development server
   ```bash
   npm run dev
   ```

5. **Open the Application**

   The application should be accessible at [http://localhost:3000](http://localhost:3000).

6. **Build for Production**

   To build the application for production, run:

   ```bash
   npm run build
   ```

   The optimized files will be in the `build` directory.

## 📝 Usage

1. **Search for Repositories**

   - Enter keywords, languages, or topics to find relevant repositories.
   - The platform fetches repositories from GitHub's API based on your search criteria.

2. **Star/Unstar Repositories**

   - Click on the "Star" button to mark repositories you find interesting.
   - The repository is added to your starred list for future reference.

3. **View Repository Details**

   - Click on any repository to view details such as its stars, forks, and programming language.

## Challenges & Setbacks

While working on this project, I faced challenges such as setting up authentication, handling deletion and updates in the database, and adding pagination for repository lists. These features are planned for future updates.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Lakhwinderr/Open-Source-Discovery/blob/main/LICENCE) file for details.

## 🤝 Contributions

Contributions are welcome! Please check the [CONTRIBUTING.md](Contributing.md) file for guidelines on how to contribute to this project.

## 🌟 Show Your Support

If you like this project, give it a ⭐️ on GitHub and share it with your community!

### Author

- [Lakhwinderr](https://github.com/Lakhwinderr)
