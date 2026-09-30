# Homework

Each assignment gets its own folder here (`hw01/`, `hw02/`, ...) with a `README.md` describing the task.

- **[Homework 1](hw01/): the hardest task in your field.** Due Oct 7. Submitted to [huangzesen/ai-in-research-homework](https://github.com/huangzesen/ai-in-research-homework), which has its own instructions; the steps below don't apply to it.

## How to submit

You submit by opening a **pull request** (PR) that adds your work to your own folder:

```
homework/hwNN/<your-github-username>/
```

You need a free [GitHub account](https://github.com/signup). You can do everything in the browser; no command line required.

**In the browser**

1. Click **Fork** at the top of this repo's page to make your own copy. You only do this once.
2. Before each assignment, open your fork and click **Sync fork** so you have the latest materials.
3. In your fork, go to `homework/hwNN/` and choose **Add file → Upload files** (or **Create new file**). Put your files under a folder named after your GitHub username, e.g. `homework/hw01/octocat/notes.md`. Commit to your fork's `main` branch.
4. Click **Contribute → Open pull request**. Title it `hwNN: <your-github-username>`.

**With git**

```bash
git clone https://github.com/<your-github-username>/ai-in-research-fall2026.git
cd ai-in-research-fall2026
mkdir -p homework/hw01/<your-github-username>
# add your files there
git add homework/hw01/<your-github-username>
git commit -m "hw01: <your-github-username>"
git push
```

Then open a pull request from your fork on GitHub.

## Rules

- **Only change files inside your own folder.**
- **Never commit API keys, passwords, or tokens.** Keep them in a `.env` file, which this repo ignores. If you commit a key by mistake, revoke it with the provider right away. Deleting the file afterwards does not make the key safe again.
- **Submissions are public.** Anyone can see this repository. Don't include personal information or data you aren't allowed to share. If you'd prefer not to submit publicly, contact the instructor.
- **Keep submissions small.** Don't upload large datasets or model files; link to them instead.
