# Deploying Beverly Hills Hotel Website to Vercel

## Quick Deploy Steps

### Option 1: Deploy via Vercel CLI (Recommended)

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy from project directory**:
   ```bash
   cd "C:\Users\MULINGWA STEPHEN\Documents\TaiStat\hotel_websites"
   vercel
   ```

4. **Follow the prompts**:
   - Set up and deploy? **Yes**
   - Which scope? **Select your account**
   - Link to existing project? **No** (first time) or **Yes** if `beverlyhotel` exists
   - Project name: **beverlyhotel**
   - Directory: **./** (just press Enter)
   - Override settings? **No**

5. **Your site will be live!** URL: `https://beverlyhotel.vercel.app`

### Option 2: Deploy via GitHub

1. Push your code to GitHub (`StephenMulingwa/hotel_websites`)
2. Go to [vercel.com](https://vercel.com) and sign in
3. Import the GitHub repository
4. Set the project name to **beverlyhotel**
5. Deploy — live at `https://beverlyhotel.vercel.app`

## Configuration Files

- **vercel.json**: Static site routing (`cleanUrls`)
- **package.json**: Project metadata

## Notes

- Site auto-deploys on every git push to main when the GitHub project is linked
- Custom domains can be added later in Vercel settings
