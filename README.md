# NorthByte Vault GitHub Pages Landing Page

This folder is a static landing page designed for GitHub Pages.

## Publish

1. Create a GitHub repository.
2. Put `index.html`, `style.css`, and `assets/northbyte-vault-logo.svg` in the repository.
3. Enable **GitHub Pages** from the repository settings.
4. Set the source to the branch/folder where these files live.

## Download link

The landing page currently points its Download buttons to `https://github.com/`.

Replace those URLs with the direct release/download URL for the NorthByte Vault ZIP you publish.

Recommended release flow:

- Upload the application ZIP to a GitHub Release.
- Copy the release asset URL.
- Replace the two `https://github.com/` links in `index.html` with that release asset URL.

## Installation text shown on the page

```powershell
cd northbyte-vault-file-edition
start.bat
```

or:

```powershell
cd northbyte-vault-file-edition
python server.py
```

Then open:

```text
http://127.0.0.1:8080
```

The page is English-only and intended as the public download/setup landing page for NorthByte Vault.
