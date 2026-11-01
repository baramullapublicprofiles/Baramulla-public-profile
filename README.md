# Baramulla Public Profiles — self-contained version

This version fixes the profile-loading problem by embedding the profile content directly inside `index.html`. It does **not** fetch `data/profile.json`, so GitHub Pages will not fail because of a missing JSON path or fetch issue.

## Publish
1. Download and extract the ZIP.
2. Open your GitHub repository: https://github.com/baramullapublicprofiles/Baramulla-public-profile
3. Upload/replace `index.html` and the `assets` folder at the repository root.
4. Keep `assets/mohammad-zubair-mir.jpg` in the same relative path.
5. Commit to `main`. GitHub Pages should redeploy automatically.

`data/profile.json` is also included as an editable backup/reference, but the live page reads the embedded data in `index.html`.
