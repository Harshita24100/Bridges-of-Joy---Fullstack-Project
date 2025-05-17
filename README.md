Bridges of Joy - Medicinal Donation Platform

Bridges of Joy is a Node.js-based web application designed to facilitate medicinal donations. This platform connects donors with individuals or organizations in need of medications, ensuring that surplus medicines reach those who need them most.

✨ Features

Donor and recipient registration

Listing and searching for available medicines

Secure and transparent donation process

Real-time notification system for donors and recipients

Comprehensive reports on donation activity

Multi-language support for global accessibility

🖼️ Screenshots

Here are some visuals of the platform:

1️⃣ Home Page

![Screenshot 2025-05-17 223825](https://github.com/user-attachments/assets/6bdae569-b3c7-4337-90e0-ffcb9499d194)


2️⃣ Our Services

![Screenshot 2025-05-17 223916](https://github.com/user-attachments/assets/9e69626c-aaf3-437f-b4d5-a8955addbd19)


3️⃣ Admin Interface

![Screenshot 2025-05-17 224020](https://github.com/user-attachments/assets/f1e275f4-15d0-4b12-9022-1be4fa95e696)


🛠 Prerequisites

Ensure you have the following installed:

Node.js (v16.x or later recommended)

MySQL (with an active server instance)

Git (optional, for cloning the repository)

🚀 Installation

1️⃣ Clone the Repository (if applicable)

git clone <repository-url>
cd <repository-directory>

2️⃣ Install Dependencies

npm install

3️⃣ Set Up the Database

Create a MySQL database.

Update the database connection details in the project. Open server.js (or a .env file if present) and configure the following:

const dbConfig = {
  host: 'localhost',
  user: 'your-username',
  password: 'your-password',
  database: 'your-database-name',
};

Run the SQL scripts (if provided) to initialize the database schema and tables.

▶️ Running the Application

1️⃣ Start the Server

npm start

By default, the server runs on http://localhost:2005. You can update the port in server.js if needed.

2️⃣ Access the Application

Open a browser and navigate to:

http://localhost:2005

📂 Directory Structure

website/
├── package.json          # Project metadata and dependencies
├── package-lock.json     # Dependency tree
├── public/               # Static files (HTML, CSS, JS, etc.)
├── server.js             # Main server entry point

🤝 Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix.

Submit a pull request with a clear description of your changes.

📜 License

This project is licensed under the MIT License.

🙏 Acknowledgments

Thanks to the developers and contributors of Node.js and MySQL.

Special thanks to the open-source community for their resources and guidance.

