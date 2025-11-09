# Publishing Your Portfolio to GitHub

Use this checklist to upload the portfolio repo to your GitHub account so hiring managers can review it.

## 1. Create a Remote Repository
1. Sign in to GitHub and click **New repository**.
2. Name it something memorable (for example, `cyber-portfolio`).
3. Leave it empty (no README, `.gitignore`, or license) because these already exist locally.

## 2. Configure Git Locally
Run these commands from the project root in your terminal:

```bash
# make sure you are inside the project folder
cd /path/to/CyberJayy

# initialize git once (skip if already initialized)
git init

# review status and stage everything
git status
git add .

# create the initial commit
git commit -m "Add cybersecurity portfolio"
```

## 3. Add the GitHub Remote
Replace `<your-username>` and `<repo-name>` with the values from GitHub:

```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
```

If you previously set a remote and need to update it, run:

```bash
git remote set-url origin https://github.com/<your-username>/<repo-name>.git
```

## 4. Push Your Work
Finally push the local commit to GitHub:

```bash
git push -u origin main
```

If your default branch is `master`, update the command accordingly.

## 5. Verify the Repository
Refresh the GitHub page to confirm that the files and commit history appear. Add a description, topics, and a README summary so visitors understand your portfolio at a glance.

---

Need help generating an SSH key, handling authentication, or automating updates? Capture those follow-up questions in `docs/README.md` so you can document them for future reference.
