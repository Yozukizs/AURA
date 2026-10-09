
## Automatic Windows installer build (GitHub Actions)

This source includes `.github/workflows/build-windows.yml`. Put the **contents** of this folder at the root of a GitHub repository (including hidden `.github`), then open **Actions → Build AURA for Windows → Run workflow**. When the build succeeds, download the **AURA-Windows-Installer** artifact from the workflow run and extract its `.exe` installer. Pushing to the repository's `main` branch also starts the build. GitHub Actions may require enabling for your repository. The installer is not code-signed, so Windows may display an unknown-publisher warning. The source bundle provided here is *not* a precompiled executable; the workflow must run successfully to create it.
