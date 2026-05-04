# Secure Chat Application with End-to-End Encryption

A secure real-time chat application built using **Node.js**, **Express.js**, **Socket.io**, and **MongoDB Atlas**.  
This project implements secure messaging using **Diffie-Hellman Key Exchange** for shared secret generation and **AES encryption** for encrypted communication.

---

## Features

- Secure real-time messaging with **Socket.io**
- **Diffie-Hellman Key Exchange** for session key generation
- **AES Encryption** for message confidentiality
- Session management using secure secrets
- MongoDB Atlas cloud database integration
- Simple and lightweight UI
- Authentication and persistent chat support

---

## Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** HTML, CSS, JavaScript
- **Real-time Communication:** Socket.io
- **Database:** MongoDB Atlas
- **Encryption:** Diffie-Hellman + AES

---

## Installation & Setup

### 1. Clone the repository

### 2. Install dependencies

Make sure **Node.js** and **npm** are installed.


### 3. Create `.env` file

Create a `.env` file in the root directory and add:

```env
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secure_session_secret
```

---

## Run the Application

Start the server:

```bash
npm start
```

If successful, you should see:

```bash
Configure public keys end.
Server is running
Connected to MongoDB Atlas
```

---

## Access the Application

Open your browser and visit:

```bash
http://localhost:3000
```


## Security Notes

- Never expose your `.env` file
- Use strong `SESSION_SECRET` values
- Store MongoDB credentials securely
- Always use HTTPS in production

---

## Contribution

Contributions are welcome.

To contribute:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## Contact

Dont contact me for issue solve yourself & commit too 


---

**Thank you for checking out this project.**
