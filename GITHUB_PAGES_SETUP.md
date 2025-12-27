# GitHub Pages Setup Instructions

## ✅ Workflow Created

The GitHub Actions workflow for deploying to GitHub Pages has been successfully created at `.github/workflows/pages.yml`.

## 🔧 Complete the Setup

To complete the GitHub Pages deployment setup, you need to configure your repository settings:

### Steps:

1. **Go to your repository on GitHub**
   - Navigate to: https://github.com/hemantgoswami/hemantgoswami

2. **Open Settings**
   - Click on the **Settings** tab in your repository

3. **Navigate to Pages Settings**
   - In the left sidebar, scroll down and click on **Pages** (under "Code and automation")

4. **Configure the Source**
   - Under **Build and deployment** section
   - For **Source**, select **GitHub Actions** from the dropdown menu
   - (Previously, this would have been set to "Deploy from a branch")

5. **Save and Deploy**
   - Once you select "GitHub Actions", the settings will be automatically saved
   - The workflow will trigger on the next push to the `main` branch

## 🚀 How It Works

The workflow (`pages.yml`) will:
- Automatically trigger on every push to the `main` branch
- Build and package your static site (all files in the repository root)
- Deploy the site to GitHub Pages
- Your site will be available at: `https://hemantgoswami.github.io/hemantgoswami/`

## 🔒 Security Features

The workflow includes:
- **Minimal permissions**: Only what's needed for Pages deployment (`contents: read`, `pages: write`, `id-token: write`)
- **Concurrency control**: Prevents conflicting deployments
- **Official GitHub Actions**: Uses verified actions from GitHub
- **Latest action versions**: Uses the most recent stable versions (v4 for checkout and configure-pages, v3 for upload, v4 for deploy)

## 📝 Workflow Details

- **File Location**: `.github/workflows/pages.yml`
- **Trigger**: Push to `main` branch
- **Jobs**: 
  - `build`: Prepares the static site artifact
  - `deploy`: Deploys to GitHub Pages

## 🎯 Next Steps

After completing the setup in Settings > Pages:
1. Make any change to your repository and push to `main` branch
2. Go to the **Actions** tab to see the workflow running
3. Once complete, visit your site at the GitHub Pages URL
4. You can delete this `GITHUB_PAGES_SETUP.md` file once setup is complete

## ❓ Troubleshooting

If the deployment doesn't work:
- Verify that GitHub Pages is enabled in Settings > Pages
- Check that the source is set to "GitHub Actions" (not "Deploy from a branch")
- Review the Actions tab for any error messages in the workflow runs
- Ensure the repository is public or you have GitHub Pages enabled for private repos (requires GitHub Pro/Team/Enterprise)

---

**Note**: This file can be safely deleted after you've completed the setup steps.
