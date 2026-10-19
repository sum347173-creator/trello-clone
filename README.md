# 📋 Trello Clone – Task Management Board

A Trello-style task management web application where users can organize work into boards, lists and cards. Built with a modern JavaScript frontend and **Supabase** for the backend.

## ✨ Features

- Create boards, lists and task cards
- Move tasks between lists (To Do → In Progress → Done)
- Edit and delete tasks
- User authentication with Supabase Auth ⚠️ (remove if not used)
- Data stored in a Supabase database
- Responsive design

⚠️ Edit this list so it matches what your app really does.

## 🧰 Tech Stack

| Layer | Technologies |
|-------|--------------|
| Frontend | JavaScript, React ⚠️ (or Next.js / HTML-CSS-JS), CSS |
| Backend / Database | Supabase (PostgreSQL, Auth) |
| Tools | Git, GitHub, VS Code, npm |

## 📁 Project Structure

```
trello-clone/
├── Trello-Clone-main/   # Application source code
├── package.json
└── README.md
```

## 📸 Screenshots

### Board View
![Board View](screenshots/Board%20View.png)

### Task Cards
![Task Cards](screenshots/Task%20Cards.png)


## 🚀 How to Run

### Prerequisites
- Node.js and npm
- A free [Supabase](https://supabase.com) account and project

### Setup
1. Clone the repository:
```bash
   git clone https://github.com/sum347173-creator/trello-clone.git
   cd trello-clone
```
2. Install dependencies:
```bash
   npm install
   cd Trello-Clone-main
   npm install
```
3. Create a `.env` file in the project and add your Supabase keys:
```
   SUPABASE_URL=your_supabase_project_url
   SUPABASE_ANON_KEY=your_supabase_anon_key
```
   ⚠️ Use the variable names your code actually reads.
4. Start the app:
```bash
   npm run dev
```
   ⚠️ Use `npm start` if your project uses that instead.

## 🔒 Security Note

Never commit your real Supabase keys. The `.env` file is ignored through `.gitignore`.

## 👨‍💻 Author

**Sumant Tiwary** – [LinkedIn](https://www.linkedin.com/in/sumanttiwary)
