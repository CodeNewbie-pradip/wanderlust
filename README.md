# ✈️ Wanderlust – Your Ultimate Travel Blog 🌍

**Wanderlust** is a simple MERN-based travel blog website. This project is designed to help people contribute to open source, upskill in React and Node.js, and master GitHub collaboration.

---

## 🔗 Project Links

- 🔎 **Live Preview:** [Wanderlust](https://github.com/krishnachavariya/wanderlust/assets/116602058/7fa3b685-22f5-418f-87c0-55af04b95a89)
- 🎨 **Design File:** [Figma Design](https://www.figma.com/file/6e1MQFQnZ9U9rQYh6WwFzH/Wanderlust---A-Travel-Blog-App?type=design&node-id=0%3A1&mode=design&t=cda03A4mmefEoSbd-1)
- 💬 **Discord Community:** [Join Here](https://discord.gg/FEkKaCRhFg)

---

## 💡 About the Project

This project aims to teach two important skills:

1. **Open Source Journey:** Learn how to contribute to open-source projects on GitHub and build confidence with Git.
2. **MERN Stack Mastery:** Understand the flow between MongoDB, Express, React, and Node.js in a full-stack application.

This is beginner-friendly and ideal for those starting with open source and modern web development.

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/wanderlust.git
cd wanderlust



2. **Navigate to the Backend Directory**

   ```bash
   cd backend
   ```

3. **Install Required Dependencies**

   ```bash
   npm i
   ```

4. **Set up your MongoDB Database**

   - Open MongoDB Compass and connect MongoDB locally at `mongodb://localhost:27017`.

5. **Import sample data**

   > To populate the database with sample posts, you can copy the content from the `backend/data/sample_posts.json` file and insert it as a document in the `wanderlust/posts` collection in your local MongoDB database using either MongoDB Compass or `mongoimport`.

   ```bash
   mongoimport --db wanderlust --collection posts --file ./data/sample_posts.json --jsonArray
   ```

6. **Configure Environment Variables**

   ```bash
   cp .env.sample .env
   ```

7. **Start the Backend Server**

   ```bash
   npm start
   ```

   > You should see the following on your terminal output on successful setup.
   >
   > ```bash
   > [BACKEND] Server is running on port 5000
   > [BACKEND] Database connected: mongodb://127.0.0.1/wanderlust
   > ```

### Setting up the Frontend

1. **Open a New Terminal**

   ```bash
   cd frontend
   ```

2. **Install Dependencies**

   ```bash
   npm i
   ```

3. **Configure Environment Variables**

   ```bash
   cp .env.sample .env.local
   ```

4. **Launch the Development Server**

   ```bash
   npm run dev
   ```

### Setting up with Docker

1.  **Ensure Docker and Docker Compose are Installed**
    
2.  **Clone the Repository**
    
   ``` bash
    
    git clone https://github.com/{your-username}/wanderlust.git
   ``` 
3.  **Navigate to the Project Directory**
    
    ```bash
    
    cd wanderlust
    
    ```
4.  **Update Environment Variables**  - If you anticipate the IP address of the instance might change, update the `.env.sample` file with the new IP address.

5.  **Run Docker Compose**
    
    ```bash
    
    docker-compose up
    ```
    This command will build the Docker images and start the containers for the backend and frontend, enabling you to access the Wanderlust application.



If you find this project interesting and inspiring, please consider showing your support by starring it on GitHub! Your star goes a long way in helping me reach more developers and encourages me to keep enhancing the project.

🚀 Feel free to get in touch with me for any further queries or support, happy to help :)
#
