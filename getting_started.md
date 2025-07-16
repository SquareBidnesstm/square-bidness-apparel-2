# Getting Started with SquareBidness App

Welcome! Follow these steps to start coding and deploying updates to [squarebidness.com](https://squarebidness.com).

---

## 1. Clone the Repository

```bash
git clone https://github.com/SquareBidnesstm/square-bidness-apparel-2.git
cd square-bidness-apparel-2
```

---

## 2. Install Dependencies

```bash
npm install
```
_or_
```bash
yarn install
```

---

## 3. Set Up Environment Variables

- If your project uses a `.env` file, copy `.env.example` (if present) to `.env` and fill out the required values.
- Example:
  ```bash
  cp .env.example .env
  ```

---

## 4. Start the Development Server

Most likely:
```bash
npm run dev
```
_or_
```bash
npm start
```
- Open [http://localhost:3000](http://localhost:3000) (or the port shown in your terminal).

---

## 5. Make Your Code Changes

- Open the folder in your favorite code editor (like VS Code).
- Add or edit features as needed.
- Test changes locally in your browser.

---

## 6. Commit and Push Your Changes

```bash
git add .
git commit -m "Describe your changes"
git push
```

---

## 7. Automatic Deployment to Vercel

- Your site is linked to Vercel for auto-deployment.
- Every push to your main branch will trigger a new deployment.
- You can view deployment progress and logs in your [Vercel dashboard](https://vercel.com/dashboard).

---

## 8. See Your Changes Live

- After a successful deployment, visit [squarebidness.com](https://squarebidness.com) to view your update.

---

## Troubleshooting

- If your changes don’t appear, check:
  - Your commit history on GitHub.
  - The Vercel dashboard for build errors.
  - That you’re pushing to the correct branch.

---

Happy coding!
