# Gaurav Singh Portfolio

This is my personal portfolio built with Jekyll and the [al-folio](https://github.com/alshedivat/al-folio) theme, hosted on GitHub Pages.

## 🚀 Local Development

### Using Docker (Recommended)

1. Make sure you have [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) installed.

2. Start the local server:
   ```bash
   docker compose up
   ```

3. Open your browser and navigate to `http://localhost:8080` to view your site.

4. Your changes will be automatically rendered in real-time (or after a few seconds).

To stop the server, press `Ctrl+C` or run:
```bash
docker compose down
```

**Note:** The first time you run this, it will download the Docker image (~400MB) and install all Ruby dependencies, which may take a few minutes.

## 📦 GitHub Pages Deployment

Your site is configured for automatic deployment to GitHub Pages:

1. **Enable GitHub Actions:**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Actions** → **General**
   - Under "Workflow permissions", select **Read and write permissions**
   - Click **Save**

2. **Configure GitHub Pages:**
   - Go to **Settings** → **Pages**
   - Under "Build and deployment", set:
     - **Source:** `Deploy from a branch`
     - **Branch:** `gh-pages` (NOT main)
   - Click **Save**

3. **Deploy:**
   - Push any changes to the `main` branch
   - GitHub Actions will automatically build and deploy your site
   - Wait for the "Deploy site" workflow to complete (~4 minutes)
   - Your site will be available at `https://gaursin13.github.io`

## 🧩 Customize

- Edit `_config.yml` to change settings like title, links, theme, etc.
- Add blog posts in `_posts/`
- Add projects in `_projects/`
- Customize pages in `_pages/`

## 📚 Resources

- [al-folio Documentation](https://github.com/alshedivat/al-folio)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

Happy hacking!
