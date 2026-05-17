# SnapYourReceiptAILegal

Public legal pages for **SnapReceipt** (App Store, privacy questionnaire, and optional in-app browser links).

Hosted via [GitHub Pages](https://pages.github.com/) from this repository.

## Live URLs (after Pages is enabled)

Replace `SnapYourReceiptsAi` if your GitHub org/username differs.

| Document | URL |
|----------|-----|
| Index | https://snapyourreceiptsai.github.io/SnapYourReceiptAILegal/ |
| Privacy Policy | https://snapyourreceiptsai.github.io/SnapYourReceiptAILegal/privacy-policy.html |
| Terms of Use | https://snapyourreceiptsai.github.io/SnapYourReceiptAILegal/terms-of-use.html |

Use the **Privacy Policy** URL in App Store Connect.

## Enable GitHub Pages (one time)

1. Push this repo to `git@github.com:SnapYourReceiptsAi/SnapYourReceiptAILegal.git`
2. On GitHub: **Settings → Pages**
3. **Build and deployment** → Source: **Deploy from a branch**
4. Branch: **main** / folder: **/ (root)**
5. Save — site goes live in 1–3 minutes

## Mobile app

`expenseTracker` opens these URLs in an in-app browser (defaults in `app/config/legalUrls.ts`). **Edit legal text only in this repo** — no duplicate copy in the app.

Optional override in `expenseTracker/.env`:

```bash
EXPO_PUBLIC_PRIVACY_POLICY_URL=https://snapyourreceiptsai.github.io/SnapYourReceiptAILegal/privacy-policy.html
EXPO_PUBLIC_TERMS_OF_USE_URL=https://snapyourreceiptsai.github.io/SnapYourReceiptAILegal/terms-of-use.html
```

## Editing content

1. Edit `privacy-policy.html` / `terms-of-use.html` here
2. Commit and push — GitHub Pages updates automatically

## Related repos

- `expenseTracker` — iOS/Android client
- `expense-tracker-backend` — API
