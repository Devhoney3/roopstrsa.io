# Roopastra-Web

This is the Roopastra-Web project. This repository contains static site sources (HTML, Pug, Tailwind CSS, assets) used to build the site.

Files added by this preparation step:
- `.gitignore` — ignores node_modules, environment files, editor config, and build outputs.
- `Roopastra-Web.code-workspace` — minimal VS Code workspace.

Local setup and initial commit

I initialized a local git repository and created the initial commit for you (see below). To create a GitHub repository and push the code, follow the "Push to GitHub" section.

Push to GitHub (PowerShell)

1) Create a remote repository using the GitHub CLI (recommended) or on the GitHub website.

Using GitHub CLI (if installed):

```powershell
# Create a new GitHub repo interactively in your account
gh repo create <OWNER>/<REPO> --public --source . --remote origin --push
```

Replace `<OWNER>/<REPO>` with your GitHub username and desired repository name. The `--push` flag pushes the current branch after creating the remote.

2) Or create the remote via the website, then add the remote locally and push:

```powershell
# (from project root)
cd 'C:\Users\Dev\Downloads\Roopastra-Web'
# add the remote returned by GitHub
git remote add origin https://github.com/<OWNER>/<REPO>.git
git branch -M main
git push -u origin main
```

Notes
- No remote was added by the preparatory steps. The repository is initialized locally and has an initial commit.
- If you use a different default branch name (e.g. `master`), adjust the `git branch -M` command accordingly.

If you'd like, I can (a) create the GitHub repo for you using the `gh` CLI (requires your authorization), or (b) add the remote URL you supply and push now. Tell me which and I'll proceed.
# Flora&Fauna - Free Tailwind CSS SaaS HTML Website Template

#### Preview

- [Demo](https://themewagon.github.io/FaunaFlora/)

#### Download

- [Download from ThemeWagon](https://themewagon.com/themes/florafauna/)

## 1. Getting Started

#### Clone Repository

```
git clone https://github.com/themewagon/FaunaFlora.git
```

NOTE: npm commands overwrite the ./public directory.

Project's source files are placed in ./src/ directory.

- ./src/assets - default static files (eg. image placeholders). You should replace them with your own files.
- ./src/tailwind/ - Tailwind config file used to build the theme. Variables used in Theme Customizer are located in tailwind.config.js file.

All your pages (templates) are stored in separate .pug files.

- ./src/pug/\*.pug

## 2. Installation

```
# Install dependencies
npm install

# Run dev server with live preview (Browsersync)
npm run watch

# Or make a production build
npm run build
```

## 3. Contact

If you have any questions, feel free to contact: support@themewagon.com

## Author

```
Design and code are completely written by PixelRocket's design and development team.
```

## License

- Design and Code is Copyright &copy; [PixelRocket](https://www.pixelrocket.store)
- Licensed under [MIT]
- Distributed by [ThemeWagon](https://themewagon.com)
