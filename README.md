# sahilicat > README.md <<EOL
# Android App Download Page

This repository hosts the download page for my Android application.

## Deployment to Cloudflare Pages

1. Place your APK file in the root directory and name it `app.apk`
2. Ensure APK size < 25MB (Cloudflare Pages limit)
3. Push to GitHub/GitLab
4. In Cloudflare Pages:
   - Connect repository
   - Build settings:
     - Framework preset: None
     - Build output directory: /
5. Deploy!

## Updating the App
1. Replace `app.apk` with new version
2. Update version number in `index.html`
3. Commit and push changes
EOL
