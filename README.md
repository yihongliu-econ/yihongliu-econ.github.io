# Yihong Liu — Academic Website

This folder is ready for GitHub Pages.

## 1. Customize the content

Search the files for `YOUR_EMAIL@ucsb.edu` and replace it with your email.

### Profile photo
Replace the initials placeholder in each HTML file:

```html
<div class="portrait placeholder"><span>YL</span></div>
```

with:

```html
<div class="portrait">
  <img src="assets/profile.jpg" alt="Yihong Liu">
</div>
```

Then put your photo at `assets/profile.jpg`.

### CV and JMP
Put your files in the top-level folder and name them:

- `cv.pdf`
- `jmp.pdf`

Or change the links in the HTML if you prefer different filenames.

## 2. Publish on GitHub Pages

1. Create a GitHub repository called `YOUR-GITHUB-USERNAME.github.io`.
2. Upload everything in this folder to the repository.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save.

Your site will appear at:

`https://YOUR-GITHUB-USERNAME.github.io/`

## Files

- `index.html` — homepage
- `research.html` — research/JMP page
- `teaching.html` — teaching page
- `assets/style.css` — all styling
- `cv.pdf` — add your CV
- `jmp.pdf` — add your JMP
