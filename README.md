# DineDesk — Restaurant Ordering & Kitchen Operations Platform

A complete restaurant ordering, table reservation, and kitchen operations management system built with React 19, TypeScript, Vite, and Tailwind CSS.

---

## How to Run in Visual Studio Code

Follow these quick steps to get DineDesk running on your local machine using Visual Studio Code:

### 1. Prerequisites
Ensure you have **Node.js** (v18 or higher) installed:
- Download and install Node.js from [nodejs.org](https://nodejs.org/).
- Verify your installation by opening your terminal or command prompt:
  ```bash
  node -v
  npm -v
  ```

---

### 2. Open the Project in VS Code
1. Launch **Visual Studio Code**.
2. Click **File** > **Open Folder...** (or `Cmd + O` on macOS / `Ctrl + K, Ctrl + O` on Windows/Linux).
3. Select the folder containing this repository.

---

### 3. Open the Integrated Terminal in VS Code
- Press ``Ctrl + ` `` (Backtick) on Windows/Linux or ``Cmd + ` `` on macOS.
- Alternatively, go to the top menu: **Terminal** > **New Terminal**.

---

### 4. Install Dependencies
In the terminal, run:
```bash
npm install
```
*(This will download all necessary packages specified in `package.json`).*

---

### 5. Start the Development Server
Run the dev server:
```bash
npm run dev
```

You should see output similar to:
```text
  VITE v8.3.0  ready in 240 ms

  ➜  Local:   http://localhost:3000/
  ➜  Network: http://<your-ip>:3000/
```

---

### 6. View the App in Your Browser
- Hold `Ctrl` (or `Cmd` on Mac) and click the `http://localhost:3000` link in your terminal, or open your web browser and go to:
  ```
  http://localhost:3000
  ```

---

## Available NPM Scripts

- `npm run dev`: Starts the Vite development server on port 3000.
- `npm run build`: Compiles and bundles production assets into the `dist/` directory.
- `npm run preview`: Locally previews the production build.
- `npm run lint`: Runs TypeScript compiler (`tsc --noEmit`) to verify type safety.

---

## Recommended VS Code Extensions

For the best developer experience in VS Code, install:
- **Tailwind CSS IntelliSense** (`bradlc.vscode-tailwindcss`) — Autocomplete and class preview.
- **ES7+ React/Redux/React-Native snippets** (`dsznajder.es7-react-js-snippets`)
- **Prettier - Code formatter** (`esbenp.prettier-vscode`)
