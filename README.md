# Backoffice Graphic Engine Editor

Static editor hosted with GitHub Pages.

## Publish steps

1. Create a new GitHub repository.
2. Add the remote:

```bash
git remote add origin https://github.com/<your-user>/<your-repo>.git
```

3. Commit and push:

```bash
git add .
git commit -m "Initial editor"
git push -u origin main
```

4. In GitHub: `Settings` -> `Pages`.
5. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. Save. Your site URL will be:

`https://<your-user>.github.io/<your-repo>/`

## Notes

- `index.html` is the page GitHub Pages serves.
- `editor.html` is kept as the working copy in this repo.
