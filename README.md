# Miami Metro LLC — Website

Official website for Miami Metro LLC, hosted on GitHub Pages at [miamimetro.us](https://miamimetro.us).

---

## 🚀 Deploying to GitHub Pages (Step by Step)

### STEP 1 — Create a New GitHub Repository

1. Go to [github.com](https://github.com) and sign in to your account (`xavidalmau9`)
2. Click the **+** icon in the top-right corner → select **"New repository"**
3. Fill in the details:
   - **Repository name:** `miamimetro`
   - **Description:** Miami Metro LLC official website
   - **Visibility:** Public ✅ (required for free GitHub Pages)
   - Leave everything else as default
4. Click **"Create repository"**

---

### STEP 2 — Upload Your Website Files

1. On your new repository page, click **"uploading an existing file"** (you'll see this link in the middle of the screen)
2. Drag and drop both files into the upload area:
   - `index.html`
   - `README.md`
3. Scroll down to **"Commit changes"**
   - Leave the default message or type: `Initial website upload`
4. Click **"Commit changes"**

---

### STEP 3 — Enable GitHub Pages

1. In your repository, click the **"Settings"** tab (top navigation bar)
2. In the left sidebar, scroll down and click **"Pages"**
3. Under **"Branch"**, click the dropdown that says `None` and select **`main`**
4. Leave the folder set to `/ (root)`
5. Click **"Save"**
6. Wait 1–2 minutes, then refresh the page
7. You'll see a green banner: **"Your site is live at https://xavidalmau9.github.io/miamimetro"**

✅ Your site is now live on GitHub Pages!

---

### STEP 4 — Connect Your Custom Domain (miamimetro.us)

#### Part A — Add the domain in GitHub

1. Still in **Settings → Pages**, find the **"Custom domain"** field
2. Type: `miamimetro.us`
3. Click **"Save"**
4. GitHub will create a file called `CNAME` in your repo automatically — leave it alone

#### Part B — Update DNS at your domain registrar

Log in to wherever you purchased `miamimetro.us` (Namecheap, GoDaddy, Squarespace, etc.) and update your DNS records:

**Add these 4 A Records** (pointing to GitHub's servers):

| Type | Host | Value | TTL |
|------|------|-------|-----|
| A | @ | 185.199.108.153 | Automatic |
| A | @ | 185.199.109.153 | Automatic |
| A | @ | 185.199.110.153 | Automatic |
| A | @ | 185.199.111.153 | Automatic |

**Add this CNAME Record** (for www redirect):

| Type | Host | Value | TTL |
|------|------|-------|-----|
| CNAME | www | xavidalmau9.github.io | Automatic |

> ⚠️ DNS changes can take anywhere from a few minutes to 48 hours to fully propagate. Usually it's under 1 hour.

#### Part C — Enable HTTPS (free SSL)

1. Go back to **Settings → Pages** in GitHub
2. Once your domain is verified, check the box **"Enforce HTTPS"**
3. Click Save

✅ Your site will now be live at **https://miamimetro.us** with a free SSL certificate.

---

## 📁 File Structure

```
miamimetro/
├── index.html      ← Main website (all-in-one file)
└── README.md       ← This file
```

---

## ✏️ Making Updates to the Website

1. Go to your repository: `github.com/xavidalmau9/miamimetro`
2. Click on `index.html`
3. Click the **pencil icon** (Edit) in the top right
4. Make your changes directly in the browser editor
5. Scroll down → click **"Commit changes"**
6. Your site will update automatically within 1–2 minutes

---

## 📧 Contact

**hello@miamimetro.us** | Miami, Florida
