# Project 3 — Database Integration

## Overview

A RESTful API with MongoDB database integration built with Node.js, Express.js, and Mongoose as part of the DecodeLabs Full Stack Development Internship 2026.

---

## Technologies Used

* Node.js v22
* Express.js
* MongoDB Atlas (Cloud Database)
* Mongoose (ODM)
* dotenv

---

## How to Run

### Installation

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file with:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
```

---

## API Endpoints

| Method | Endpoint     | Description     |
| ------ | ------------ | --------------- |
| GET    | `/users`     | Get all users   |
| GET    | `/users/:id` | Get single user |
| POST   | `/users`     | Create new user |
| PUT    | `/users/:id` | Update user     |
| DELETE | `/users/:id` | Delete user     |

---

## Request Body (POST / PUT)

```json
{
    "name": "Shahan Waheed",
    "email": "shahanwaheed43@gmail.com",
    "city": "Attock"
}
```

---

## Database Schema

* **name** — String, required, min 2 chars
* **email** — String, required, unique, validated
* **city** — String, required
* **createdAt** — Date, auto generated

---

## Intern

**Shahan Waheed**
DecodeLabs Batch 2026


