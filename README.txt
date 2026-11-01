BARAMULLA PUBLIC PROFILES — FIXED GITHUB PAGES PACKAGE

This version fixes the data-loading failure by embedding a complete fallback copy of the profile data directly in index.html. It also keeps data/profile.json as the editable source. If GitHub Pages cannot fetch that JSON, the page still renders the embedded copy rather than showing a blank profile.

UPLOAD THESE ITEMS TO THE ROOT OF YOUR EXISTING REPOSITORY:
- index.html
- data/ (containing profile.json)
- assets/ (containing profile-photo.jpg)
- README.txt

IMPORTANT: The repository's actual URL path is /Baramulla-public-profile/ (capital B, singular profile). Do not create another repository. Upload/replace these files in the existing repository:
https://github.com/baramullapublicprofiles/Baramulla-public-profile

On GitHub:
1. Open the repository.
2. Add file -> Upload files.
3. Drag index.html, README.txt, and the data and assets folders from the extracted ZIP.
4. Confirm replacement of index.html and README.txt if prompted.
5. Commit changes to main.
6. Wait for Actions -> pages build and deployment to show a green tick.
7. Refresh the website using Cmd+Shift+R (hard refresh).

REPOSITORY ROOT MUST LOOK LIKE:
index.html
README.txt
data/profile.json
assets/profile-photo.jpg

The website is designed to use relative paths so it works in a GitHub Pages project site. The external JSON is loaded when available; embedded data is the fallback. Keep both copies in sync when editing profile content. For a new activity, edit data/profile.json and also update the embedded data in index.html, or ask for a refreshed package.

Editorial note: some entries intentionally remain marked as needing direct source links. Do not present those as independently verified until sources are added.
