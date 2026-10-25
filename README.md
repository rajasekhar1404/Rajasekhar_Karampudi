# Rajasekhar Karampudi — About Me

A responsive, dependency-free personal portfolio built with HTML and CSS, featuring CentralHub, a personal mobile app project.

## Publish with GitHub Pages

1. Create a **public** repository named `Rajasekhar_Karampudi` under the `rajasekhar1404` GitHub account. Leave it empty (do not add a README, license, or `.gitignore`).
2. From this project folder in PowerShell, run:

   ```powershell
   git init -b main
   git add .
   git commit -m "Create personal portfolio"
   git remote add origin https://github.com/rajasekhar1404/Rajasekhar_Karampudi.git
   git push -u origin main
   ```

3. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
4. The workflow in `.github/workflows/pages.yml` deploys the site after the push. Once its run succeeds, the page will be available at:

   <https://rajasekhar1404.github.io/Rajasekhar_Karampudi/>

## Customize

- Update the page copy and links in `index.html`.
- Adjust colors, layout, and responsive styles in `styles.css`.
- Push changes to `main` to publish an update.
