
### **Criminal Database Management System (CDBMS) with Blockchain Security**  

This project is a **full-stack application** designed to store and manage criminal records securely, leveraging **MongoDB**, **Node.js**, **React.js**, and **Ethereum Blockchain** for data integrity.

---

### **1. Database (MongoDB)**
- **Stores data** about criminals, crimes, and police officers.
- Uses **Mongoose schemas** for structured data storage.
- Ensures data relationships with **ObjectId references**.

### **2. Backend (Node.js + Express)**
- **Handles API requests** for fetching and managing criminal data.
- Uses **Express.js** to create RESTful APIs.
- Connects to **MongoDB** using **Mongoose**.
- Implements **CORS** to allow frontend requests.

### **3. Blockchain Security (Solidity Smart Contract)**
- Records crime data securely using **Ethereum blockchain**.
- Prevents **tampering** of crime records.
- Uses **events** to log new crimes immutably.

### **4. Frontend (React.js)**
- **Fetches** criminal records from the backend API.
- **Displays** a list of criminals dynamically.
- Uses **React hooks** (`useEffect`, `useState`) for state management.


📦 Criminal-DBMS  
┣ 📂 backend  
┃ ┣ 📜 server.js  (Express backend)  
┃ ┣ 📜 models/ (Mongoose schemas)  
┃ ┗ 📜 routes/ (API endpoints)  
┣ 📂 frontend  
┃ ┣ 📜 src/  
┃ ┃ ┣ 📜 App.js  (React frontend)  
┃ ┃ ┗ 📜 components/  
┣ 📂 blockchain  
┃ ┣ 📜 CrimeRegistry.sol  (Smart contract)  
┃ ┗ 📜 hardhat.config.js  
┣ 📜 README.md  
┣ 📜 package.json  
┗ 📜 .env  
