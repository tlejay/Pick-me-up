# How to Deploy PICK-ME-UP Proposal

Since you have a GitHub repository, the easiest way to host this publicly with free updates is **GitHub Pages**.

## Option 1: GitHub Pages (Recommended)

1.  **Commit & Push** your changes:
    ```bash
    git add index.html
    git commit -m "Add proposal viewer"
    git push origin main
    ```

2.  **Enable GitHub Pages**:
    - Go to your repository on GitHub.com.
    - Click **Settings** > **Pages** (in the sidebar).
    - Under **Branch**, select `main` and click **Save**.

3.  **View Your Proposal**:
    - Your site will be live at: `https://<your-username>.github.io/<repo-name>/`
    - Any time you edit `docs/proposal.md` and push, the site updates automatically (usually within roughly 60 seconds).
    
## Option 2: Surge.sh (Instant Command Line)

If you prefer a command-line deployment without configuring GitHub settings:

1.  **Run Surge**:
    ```bash
    npx surge .
    ```
    *(You may need to create an account/login on the first run)*

2.  **Set Domain**:
    - It will suggest a random domain (e.g., `pick-me-up-proposal.surge.sh`).
    - Press `Enter` to confirm.

3.  **Real-time Updates**:
    - To update, just run `npx surge .` again.

## Local Viewing
To view it on your machine immediately:
```bash
open index.html
```
*(Note: If the markdown doesn't load due to browser security settings, run a local server: `npx serve .` or `python3 -m http.server`)*
