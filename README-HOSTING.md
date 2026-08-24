# AURA — Formal Luxury Website

## GitHub Pages hosting

### 1. Create the repository
1. Sign in to GitHub.
2. Click **New repository**.
3. For the cleanest URL, name it exactly:
   `auramobile.github.io`
4. Set it to **Public**.
5. Create the repository.

### 2. Upload the website
1. Open the new repository.
2. Click **Add file → Upload files**.
3. Open the extracted AURA website folder on your computer.
4. Select **everything inside the folder**, including:
   - `index.html`
   - all other `.html` pages
   - `assets` folder
   - CSS/JS files
5. Drag them into GitHub.
6. Click **Commit changes**.

IMPORTANT:
`index.html` must be in the repository root, not inside another folder.

### 3. Turn on GitHub Pages
1. Open **Settings**.
2. Select **Pages** from the left menu.
3. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**.

### 4. Open the website
After GitHub finishes publishing, open:

https://auramobile.github.io/

### 5. If you already have `aura-smartphones` repository
You have two choices:

- For `https://auramobile.github.io/`, create/rename the repository to:
  `auramobile.github.io`
- If the repository is already `auramobile.github.io`, replace its contents with this website.

### 6. Common upload error
If GitHub says:
"Sorry, a file exists where you're trying to create a subdirectory"

Do not create an `assets` folder manually if an `assets` file already exists.
Instead:
1. Delete the conflicting file.
2. Upload the complete `assets` folder from your computer.
3. Commit again.

### 7. Updating the website later
Edit/replace the files in the repository and commit the changes.
GitHub Pages will automatically rebuild the site.

## Pages
- Home
- Services
- AURA Secure
- AURA Care
- Exchange & Upgrade
- About AURA
- Support
