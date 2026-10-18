# FitFactor Privacy Policy Repository

This repository hosts the public Privacy Policy for the **FitFactor** (**FitFactor Gym Workout
Tracker**) Android application.

## Hosting on GitHub Pages

Follow these simple steps to make your privacy policy publicly accessible for Google Play Console:

1. **Commit and Push to GitHub**:
   ```bash
   git add index.html PRIVACY_POLICY.md
   git commit -m "Update Privacy Policy for FitFactor"
   git push origin main
   ```

2. **Enable GitHub Pages**:
    - Open your repository on GitHub: `https://github.com/quatrilabs/fitfactor-privacy-policy` (or
      `https://github.com/quatrilabs/workout-tracker-privacy-policy`)
    - Navigate to **Settings** > **Pages** (under the Code and automation section).
    - Under **Build and deployment** -> **Source**, select **Deploy from a branch**.
    - Under **Branch**, select `main` (or `master`) and `/ (root)`, then click **Save**.

3. **Get Your Public URL**:
    - After deployment, GitHub Pages will publish your site at:
      `https://quatrilabs.github.io/fitfactor-privacy-policy/` (or your repository's Pages URL)
    - Copy this URL and paste it into:
        - **Google Play Console** -> App Content -> Privacy Policy
        - Your app's **Settings / About** screen inside the Android app.
