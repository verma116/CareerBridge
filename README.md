
# CareerBridge

CareerBridge is a full-stack **job portal application** that connects job seekers with employers.
It provides a seamless platform for posting jobs, applying to openings, and managing career opportunities.



## 🚀 Features

* 👤 **User Authentication & Authorization** – secure login and signup with JWT
* 💼 **Job Management** – employers can post, update, and delete job listings
* 📄 **Application Tracking** – candidates can apply to jobs and manage their applications
* 🔍 **Search & Filter** – find jobs by category, title, or keywords
* 🗄 **Database Integration** – persistent data storage with MongoDB
* ⚡ **REST API** – modular backend built with Express



## 🛠 Tech Stack

**Frontend**

* React.js
* HTML5, CSS3, JavaScript
* Axios (API calls)

**Backend**

* Node.js, Express.js
* MongoDB & Mongoose
* JWT Authentication
* dotenv for environment variables

**Other Tools**

* Git & GitHub for version control
* Postman for API testing


## 📂 Folder Structure

CareerBridge/
│-- backend/            # Backend server
│   │-- controllers/    # Route logic
│   │-- database/       # DB connection
│   │-- middlewares/    # Authentication & error handling
│   │-- app.js          # Express app setup
│   │-- server.js       # Entry point
│   └-- package.json    # Backend dependencies
│
│-- frontend/ (if included) # React frontend
│-- package.json        # Frontend dependencies
│-- .gitignore
│-- .gitattributes
│-- README.md           # Project documentation
```


## ⚙️ Installation & Setup

### Prerequisites

* Node.js (v14+ recommended)
* MongoDB installed & running locally (or Atlas connection string)
* Git

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CareerBridge.git
cd CareerBridge
```

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside `backend/`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Run the backend server:

```bash
npm start
```

### 3. Setup Frontend

```bash
cd ..
npm install
npm start
```

The frontend will run on `http://localhost:3000` and backend on `http://localhost:5000`.


## 📸 Screenshots
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fc4b2212-5f04-42f5-a4fa-637e75f74d73" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fc4b2212-5f04-42f5-a4fa-637e75f74d73" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8ba22b8c-cf5e-4bc5-af05-48ead3295324" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/590395a0-1813-43ce-bf6e-ca01477792db" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0d302ed0-ff58-489f-9e7a-b8e0b9e6a606" />












