# Abhishek Giridhar Bhat — Portfolio

Operations Leader | Technical Operations Architect

Static portfolio site built with [Oat UI](https://oat.ink/). Hosted on GitHub Pages.

## Local preview

Open `index.html` in a browser, or use a simple server:

```bash
# Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. **Create a new repository** on GitHub (e.g. `abhishek-portfolio` or `username.github.io` for a user site).

2. **Add the remote and push** (replace `YOUR_USERNAME` and `YOUR_REPO` with your GitHub username and repo name):

   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git branch -M main
   git push -u origin main
   ```

3. **Turn on GitHub Pages**  
   In the repo: **Settings → Pages → Build and deployment**  
   - **Source**: Deploy from a branch  
   - **Branch**: `main` / **(root)**  
   - Save.

4. **Open your site**  
   After a minute or two it will be at:  
   - `https://YOUR_USERNAME.github.io/YOUR_REPO/`  
   - Or `https://YOUR_USERNAME.github.io/` if the repo is named `YOUR_USERNAME.github.io`.

## License

© Abhishek Giridhar Bhat. All rights reserved.
