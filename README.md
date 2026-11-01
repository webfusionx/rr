# Real & Rare (Pvt.) Ltd.

Official sovereign mineral exploration and joint venture portal for Real & Rare (Pvt.) Ltd., operating under statutory concession frameworks in Gilgit-Baltistan and Northern Pakistan.

- **SECP CUIN**: 0239108
- **Corporate Memberships**: KCOCI & FPCCI
- **Regulatory Compliance**: Gilgit-Baltistan Department of Mines & Minerals

---

## Project Structure

```
├── index.html         # Main entry point (Single-Page Portal)
├── assets/            # High-resolution media assets
│   ├── rr-logo.jpg                  # Interlocking 3D gold monogram & favicon
│   ├── hero-mountains.jpg           # Karakoram geological terrain background
│   ├── ceo-husnain-khokhar.jpg      # Founder & CEO portrait
│   ├── director-junaid-husnain.jpg  # Executive Director portrait
│   ├── ghizer-copper-lease.jpg      # Project 1: Ghizer Copper Mining Lease
│   ├── diamer-lead-lease.jpg        # Project 2: Diamer Lead Mining Lease
│   ├── hunza-critical-minerals.jpg  # Project 3: Hunza Critical Minerals Survey
│   └── wechat-qr.jpg                # Asia-Pacific WeChat direct QR code
├── vercel.json        # Production headers, clean URLs & cache optimization
└── .gitignore         # Ignores system files, logs, and binaries
```

---

## Deploying to Vercel

### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2: Git Integration
1. Push this folder to a GitHub, GitLab, or Bitbucket repository.
2. In the [Vercel Dashboard](https://vercel.com/new), select **Add New Project** and import the repository.
3. Framework Preset: **Other** (Static Site).
4. Click **Deploy**. Vercel will serve `index.html` instantly with zero build configuration.
