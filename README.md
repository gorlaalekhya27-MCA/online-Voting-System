
# 🗳️ Online Voting System

A secure, efficient, and transparent **Online Voting System** web application designed to digitize the election process. This system allows voters to register and securely cast their votes remotely, while giving administrators full control over election management, candidate listings, and real-time result monitoring.

---

## 📌 Features

### 👤 Voter Panel
* **Secure Authentication:** Voter registration and login with encrypted credentials.
* **Eligibility Verification:** Simple verification using unique identifiers (e.g., Voter ID / Student ID).
* **Single Vote Enforcement:** System restrictions that prevent double voting within the same election.
* **Profile Management:** View and update voter profile metrics.

### 🛠️ Admin Dashboard
* **Election Management:** Create, update, or end multiple active elections.
* **Candidate Management:** Add, edit, or remove candidates assigned to specific electoral positions.
* **Voter Control:** Track voter registration lists and audit compliance metrics.
* **Real-time Analytics:** Automated tallying showing clear, real-time vote distribution and percentages.

---

## 💻 Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript / ReactJS, Bootstrap
* **Backend:** Node.js / PHP / Python (Django)
* **Database:** MySQL / MongoDB
* **Security:** Password hashing (bcrypt), Session tracking, and input sanitisation

---

## 📂 Project Structure

```text
online-voting-system/
│
├── public/                 # Static assets (images, CSS, frontend JS)
├── views/                  # UI Templates / Pages (Login, Dashboard, Vote)
├── config/                 # Database credentials and configuration
├── controllers/            # Logic handling for routes (Voter, Admin, Vote management)
├── models/                 # Database schemas (Voter, Candidate, Election)
├── routes/                 # Endpoint paths mappings
├── server.js (or index.php)# Core entry point file
└── README.md
```

---

## 🚀 Getting Started

Follow these instructions to set up a local copy of the project.

### Prerequisites
Make sure you have the following installed:
* A modern browser (Chrome, Edge, Firefox)
* Node.js & npm **OR** XAMPP/WAMP (if using PHP/MySQL)
* Database server (MySQL instance or MongoDB Atlas account)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd online-voting-system
   ```

2. **Install dependencies:**
   *(For Node.js environments)*
   ```bash
   npm install
   ```
   *(For PHP environments, move the directory to your `htdocs` or `www` folder)*

3. **Database Setup:**
   * Create a new database named `voting_db`.
   * Import the provided SQL backup file (e.g., `database.sql`) or let your ORM generate schemas on run.

4. **Environment Configuration:**
   Create a `.env` file in the root directory and update your server configurations:
   ```env
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=your_password
   DB_NAME=voting_db
   PORT=5000
   ```

5. **Run the Application:**
   *(For Node.js)*
   ```bash
   npm start
   ```
   

---

