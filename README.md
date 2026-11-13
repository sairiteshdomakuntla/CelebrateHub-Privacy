# CelebrateHub — Official Privacy & Legal Compliance Portal

> Public legal portal, Privacy Policy, Terms of Service, and Google OAuth 2.0 verification pages for **CelebrateHub** — Event Services Marketplace & Management Platform.

---

## 🌐 Live Production URLs (Deployed on Vercel)

| Document | Direct URL | Google Cloud Console OAuth Field |
| :--- | :--- | :--- |
| **Privacy Policy** | `https://celebratehubbusiness.vercel.app/` *(or `/index.html`)* | **Application privacy policy link** *(Mandatory)* |
| **Terms of Service** | `https://celebratehubbusiness.vercel.app/terms.html` | **Application terms of service link** *(Recommended / Required)* |
| **Data Deletion Instructions** | `https://celebratehubbusiness.vercel.app/data-deletion.html` | **User Data Deletion / Compliance URL** |
| **Home Page** | `https://celebratehubbusiness.vercel.app/` | **Application home page link** |

---

## 📋 Google Cloud Console OAuth Consent Screen Fields

When configuring your OAuth consent screen in [Google Cloud Console](https://console.cloud.google.com/apis/credentials/consent):

| Field in Google Cloud Console | Exact Value to Enter |
| :--- | :--- |
| **App name** | `CelebrateHub` |
| **User support email** | `celebratehub.business@gmail.com` |
| **App logo** | *(Optional)* CelebrateHub `CH` monogram brand mark |
| **Application home page** | `https://celebratehubbusiness.vercel.app/` |
| **Application privacy policy link** | `https://celebratehubbusiness.vercel.app/` |
| **Application terms of service link** | `https://celebratehubbusiness.vercel.app/terms.html` |
| **Authorized domains** | `celebratehubbusiness.vercel.app` *(or `vercel.app`)* |
| **Developer contact information** | `celebratehub.business@gmail.com` |

> **Note on Authorized Domains:** Google Cloud Console expects domains without `https://` or trailing slashes (e.g. `celebratehubbusiness.vercel.app` or `vercel.app`).

### OAuth Scopes to Request
For standard Google Sign-In authentication:
- `.../auth/userinfo.email` — See primary Google Account email address
- `.../auth/userinfo.profile` — See personal info including name and profile picture
- `openid` — Authenticate using OpenID Connect

---

## 🛡️ Key Google Verification Requirements Satisfied

This portal has been tailored specifically to comply with **Google Cloud OAuth App Verification** standards:

1. **Explicit Google API Services User Data Policy Compliance:**
   > *"CelebrateHub's use and transfer of information received from Google APIs to any other app will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements."*
2. **Transparent Scope Disclosures:** Dedicated table detailing exactly why `openid`, `userinfo.email`, and `userinfo.profile` are requested and how they are used.
3. **No Sale of Google User Data:** Formal declaration that user data is never sold, licensed, or transferred to third-party data brokers, ad networks, or commercial entities.
4. **No AI/ML Model Training:** Explicit disclosure that data obtained through Google APIs is never utilized to train generalized AI models.
5. **Human Inspection Prohibited:** Policy guarantees employee/contractor review of user data is strictly prohibited unless explicitly requested by the user for technical support.
6. **Data Deletion Instructions (`data-deletion.html`):** Complete, step-by-step instructions for in-app self-service erasure and direct support email requests (`celebratehub.business@gmail.com`).
7. **Platform Context:** Custom-tailored to CelebrateHub's architecture (event planning, vendors, leads, Neon PostgreSQL, Razorpay payments, and JWT sessions).

---

## 💻 Tech Stack & Deployment

- **Hosting:** Vercel (`https://celebratehubbusiness.vercel.app/`) and GitHub Pages ready.
- **Frontend:** Pure semantic HTML5, modern modular CSS3, responsive two-column documentation layout, zero external framework dependencies or build scripts needed.
- **Design System:** Minimalist, high-trust corporate legal documentation inspired by Stripe, Linear, and Vercel Legal standards.
