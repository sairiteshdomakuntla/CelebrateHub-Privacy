# CelebrateHub — Official Privacy & Legal Compliance Portal

> Public legal portal, Privacy Policy, Terms of Service, and Google OAuth 2.0 verification pages for **CelebrateHub** — Event Services Marketplace & Management Platform.

---

## 🌐 Live URLs (Once GitHub Pages is Enabled)

| Page | URL | Purpose for Google Cloud Console |
| :--- | :--- | :--- |
| **Privacy Policy** | `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/` | **Application Privacy Policy link** *(Required)* |
| **Terms of Service** | `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/terms.html` | **Application Terms of Service link** *(Required / Recommended)* |
| **Data Deletion Instructions** | `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/data-deletion.html` | **User Data Deletion / Compliance link** |
| **Home Page** | `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/` | **Application Home page link** |

---

## 📋 Google Cloud Console OAuth Consent Screen Fields

When configuring your OAuth consent screen at [Google Cloud Console](https://console.cloud.google.com/apis/credentials/consent):

| Field in Google Cloud Console | Recommended Value |
| :--- | :--- |
| **App name** | `CelebrateHub` |
| **User support email** | `sairiteshdomakuntla@gmail.com` (or your preferred admin email) |
| **App logo** | *(Optional)* Upload CelebrateHub brand icon (`CH` icon) |
| **Application home page** | `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/` |
| **Application privacy policy link** | `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/` |
| **Application terms of service link** | `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/terms.html` |
| **Authorized domains** | `github.io` *(and your production API/app domain if applicable)* |
| **Developer contact information** | `sairiteshdomakuntla@gmail.com` |

### OAuth Scopes to Request
For standard Google Sign-In authentication:
- `.../auth/userinfo.email` — See primary Google Account email address
- `.../auth/userinfo.profile` — See personal info including name and profile picture
- `openid` — Authenticate using OpenID Connect

---

## 🚀 How to Enable GitHub Pages (Instant Hosting)

1. Push these files to your repository:
   ```bash
   cd d:\proj\CelebrateHub-Privacy
   git add .
   git commit -m "Add Google OAuth compliant Privacy Policy, Terms, and Data Deletion pages"
   git push origin main
   ```
2. Open your repository in your browser:
   [https://github.com/sairiteshdomakuntla/CelebrateHub-Privacy/settings/pages](https://github.com/sairiteshdomakuntla/CelebrateHub-Privacy/settings/pages)
3. Under **"Build and deployment"**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/(root)`
4. Click **Save**.
5. Within 1-2 minutes, GitHub will publish your site live at:  
   👉 `https://sairiteshdomakuntla.github.io/CelebrateHub-Privacy/`

---

## 🛡️ Key Google Verification Requirements Included

This privacy page has been tailored specifically to satisfy **Google Cloud OAuth App Verification** standards:

1. **Prominent Application Identity:** Clearly identifies CelebrateHub as an event services marketplace platform.
2. **Explicit Google API Services User Data Policy Compliance:**
   > *"CelebrateHub's use and transfer of information received from Google APIs to any other app will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements."*
3. **Transparent Scope Justification:** Dedicated section detailing exactly why `openid`, `userinfo.email`, and `userinfo.profile` are requested and how they are used.
4. **No Sale of Google User Data:** Express declaration that user data is never sold to third parties, data brokers, or advertising networks.
5. **No AI Model Training:** Explicit disclosure that Google data is not used for generalized AI/ML training.
6. **Data Deletion Instructions:** Dedicated step-by-step instructions (`data-deletion.html`) allowing users to request account erasure within the app or via direct email.
7. **Platform Context:** Custom-tailored to CelebrateHub's architecture (event planning, vendors, leads, Neon PostgreSQL, Razorpay payments, and JWT sessions).

---

## 🎨 Visual Identity & Styling

Built using standard HTML5, CSS3, and Google Fonts (`Inter`):
- Deep Indigo/Navy background (`#0E0B22`, `#120F2B`, `#1A163B`)
- Brand Purple (`#7C5CFF`), Celebration Magenta (`#D6307F`), and Amber Gold (`#FFC53D`)
- Fully responsive across desktop, tablet, and mobile screens
- Print-ready and accessible with high-contrast text and dark-mode optimization
- Zero runtime dependencies or build steps required
