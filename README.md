# ZekretLabs CRM - Vercel Deployment

## 📁 File Structure

```
zekretlabs-crm/
├── public/
│   └── index.html    <- Your CRM app
├── vercel.json       <- Vercel configuration
└── package.json      <- Project info
```

## 🚀 Deploy Instructions

### Upload to GitHub:

1. Create repo at: https://github.com/new
2. Name it: `zekretlabs-crm`
3. Upload ALL files maintaining the structure:
   - Upload `vercel.json`
   - Upload `package.json`
   - Create folder `public`
   - Upload `index.html` into the `public` folder

4. Commit changes

### Connect to Vercel:

1. Go to vercel.com
2. Import your GitHub repo
3. Vercel will auto-detect settings
4. Click "Deploy"
5. ✅ Done!

## ⚠️ IMPORTANT

The `public` folder is required! Make sure your structure looks like:

```
repo-root/
  public/
    index.html  <- Must be here!
  vercel.json
  package.json
```

## 🎯 After Deployment

Your CRM will be live at: `https://your-project.vercel.app`

1. Open the URL
2. Sign up (you'll be admin)
3. Import your 646 leads
4. Invite team members
5. Start working!
