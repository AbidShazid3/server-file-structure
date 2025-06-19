# 🚀 Express.js + TypeScript Starter

A minimal boilerplate for building a backend server using **Node.js**, **Express**, and **TypeScript**.

---

## 📦 Technologies Used

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- MongoDB (Mongoose)
- Dotenv
- Nodemon

---

## 🛠 Installation & Setup

### 1️⃣ Initialize the Project

creating a src folder and inside src create app folder, app.ts, server.ts file

```bash
npm init -y
```
### 2️⃣ Install TypeScript, Express & mongoose
```bash
npm install -D typescript express mongoose
```

### 3️⃣  Initialize TypeScript Configuration
```bash
tsc --init
```

#### Then in tsconfig.json, configure these options:
```bash
// line ~30
"rootDir": "./src/",

// line ~62
"outDir": "./dist/",
```

### 4️⃣(Optional) Install TypeScript Globally
```bash
npm install -g typescript
```