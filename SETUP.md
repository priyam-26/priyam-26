# Set up your Sakura GitHub profile

1. On GitHub, create a **public** repository named exactly `priyam-26` (same as your username).
2. Upload the contents of this folder to the root of that repository. Make sure `.github/workflows/grow-sakura.yml` is included.
3. Open **Settings → Actions → General → Workflow permissions** and allow read and write permissions if your account settings require it. The workflow also declares `contents: write`.
4. Open **Actions → Grow my sakura tree → Run workflow** to generate the first live tree.
5. Check the README on `https://github.com/priyam-26`.

The workflow runs every day at 00:00 IST. It uses GitHub's automatically provided `GITHUB_TOKEN`; you do not need to create or paste a personal access token.

The initial `assets/plant.svg` is generated from demo values so the README has an image immediately. After the first successful workflow run, it is replaced with data fetched for `priyam-26`.

If GitHub Actions is disabled for the repository or organization, enable it before running the workflow.
