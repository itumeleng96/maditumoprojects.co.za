# Maditumo Projects Website

## How to Publish on GitHub Pages with Your Domain

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click the **+** button → **New repository**
3. Name it exactly: `maditumoprojects.co.za`
4. Set it to **Public**
5. Click **Create repository**

### Step 2: Upload the Website Files
1. In your new repository, click **Add file** → **Upload files**
2. Upload both files:
   - `index.html`
   - `CNAME`
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to your repository **Settings**
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: **main**, folder: **/ (root)**
5. Click **Save**

### Step 4: Connect Your Domain (maditumoprojects.co.za)
Log in to your domain registrar (where you bought maditumoprojects.co.za) and add these DNS records:

**A Records** (point to GitHub):
| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

**CNAME Record** (for www):
| Type | Name | Value |
|------|------|-------|
| CNAME | www | maditumoprojects.co.za |

### Step 5: Verify in GitHub
1. Back in repository **Settings → Pages**
2. Under **Custom domain**, type: `maditumoprojects.co.za`
3. Click **Save**
4. Tick **Enforce HTTPS** (once it appears)

### Done! 🎉
Your site will be live at **https://maditumoprojects.co.za** within 24–48 hours (DNS propagation time).# maditumoprojects.co.za
