# HookProject

## 🚀 Getting Started

Follow these steps to set up the project locally:

### 1️⃣ **Make Sure Node.js is Installed**

Check if Node.js is installed:
```bash
node -v
```

If Node.js is **not installed**, follow these steps:
- **Using Homebrew (Mac):**
  ```bash
  brew install node
  ```

- **Using nvm (Node Version Manager):**
  ```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
  source ~/.bashrc  # or ~/.zshrc depending on your shell
  nvm install node
  ```

- **Download Directly:**  
  Visit [https://nodejs.org/](https://nodejs.org/) and download the latest LTS version.

Verify installation:
```bash
node -v
npm -v
```

### 2️⃣ **Clone the Repository**
```bash
git clone https://github.com/jerrybenn/hookProject.git
```

### 3️⃣ **Navigate to the Project Directory**
```bash
cd hookProject
```

### 4️⃣ **Checkout to Your Branch Before Coding**
List all branches:
```bash
git branch -a
```

Switch to your branch:
```bash
git checkout <your-branch-name>
```

If you need to create a new branch:
```bash
git checkout -b <new-branch-name>
```

### 5️⃣ **Install Dependencies**
```bash
npm install
```

### 6️⃣ **Run the Project**
```bash
npm start
```

---

## ✅ Contributing Guidelines
- Always pull the latest changes before starting:
  ```bash
  git pull origin main
  ```
- Make descriptive commits:
  ```bash
  git add .
  git commit -m "[FEATURE] Add login functionality"
  git push origin <your-branch-name>
  ```
- Open a pull request when you're ready for review.

Happy coding! 🎯
