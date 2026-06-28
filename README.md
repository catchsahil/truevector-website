# TrueVector India Partners — Website v19

## v19 Changes (May 2026)
- **Country field mapping fix:** Country/Region now submits to Contact object (0-1) instead of Company object (0-2), matching the updated HubSpot form configuration. This ensures Country appears directly on the Contact record for cleaner data and easier filtering.

## v18 Changes
- **Form backend migration:** FormSubmit.co → HubSpot Forms API (formId `119e463c-434f-488f-b32e-7433c4a23fe7`)
- **Lead capture upgrade:** Form submissions now auto-create contact records in HubSpot CRM with email notification to sahil@truevectorindia.com
- **GDPR consent:** Added required privacy consent checkbox on the enquiry form
- **Privacy Policy updated:** Replaced FormSubmit data processor entry with HubSpot

## Deploy to GitHub Pages

This repo is ready for GitHub Pages:

1. Go to **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, Folder: **/ (root)**
4. Click **Save**

Site goes live at `https://catchsahil.github.io/truevector-website/` within 2 minutes.

## Point Custom Domain

In GoDaddy DNS for `truevectorindia.com`:

| Type  | Name | Value                    | TTL |
|-------|------|--------------------------|-----|
| A     | @    | 185.199.108.153          | 600 |
| A     | @    | 185.199.109.153          | 600 |
| A     | @    | 185.199.110.153          | 600 |
| A     | @    | 185.199.111.153          | 600 |
| CNAME | www  | catchsahil.github.io     | 600 |

Then in GitHub Pages settings, enter `www.truevectorindia.com` → tick **Enforce HTTPS**.

---

© 2026 TrueVector India Partners Private Limited · CIN: U70200MR2026PTC475960
