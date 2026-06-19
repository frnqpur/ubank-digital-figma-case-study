# Security Cleanup — UBank Digital

## Purpose
Security cleanup bertujuan memastikan project aman untuk recruiter, CV, GitHub, dan website portfolio tanpa menampilkan data sensitif atau klaim yang menyesatkan.

## Project Status
UBank Digital adalah Figma UI/UX prototype. Tidak ditemukan indikasi bahwa project ini memiliki:

- Backend source code
- Database
- Migration
- Environment file
- API key
- Auth implementation
- Payment processing
- Banking API integration

Namun, desain UI tetap bisa menampilkan data dummy yang harus dibersihkan sebelum publikasi.

## Data That Must Be Masked
Masking wajib untuk:

- Full card number
- CVV
- Phone number
- Email address
- Date of birth
- Address
- Real-looking account number
- Real-looking user identity
- Any private note visible in design

## Recommended Masking Format
Gunakan format berikut:

```text
Card Number: 1234 **** **** 1121
CVV: ***
Email: user@example.com
Phone: +62 812 **** ****
Date of Birth: DD/MM/YYYY
Account Number: **** **** 1234
```

## Figma Cleanup Checklist
- [ ] Duplicate original Figma file before editing
- [ ] Do not edit the raw/original file directly
- [ ] Mask sensitive-looking dummy data
- [ ] Fix visible typo
- [ ] Standardize language
- [ ] Standardize currency
- [ ] Remove inconsistent names
- [ ] Re-check prototype links
- [ ] Re-export screenshots after cleanup
- [ ] Re-record video if sensitive data still appears

## Portfolio Cleanup Checklist
- [ ] Do not upload raw files that are not needed
- [ ] Do not publish private/internal source if project is confidential
- [ ] Do not claim backend integration
- [ ] Do not claim real payment or real banking capability
- [ ] Do not claim production launch
- [ ] Use "prototype", "concept", or "UI/UX case study"
- [ ] Keep Figma link view-only
- [ ] Use public-safe screenshots only
- [ ] Use a clean video demo only

## GitHub Safety
Safe to upload:

```text
README.md
case-study.md
screenshots/*.png
video-demo link
figma prototype link
portfolio content
```

Avoid uploading:

```text
Raw private design files if not intended for public
Unmasked screenshots
Unmasked video
Internal notes
Files containing credentials or private information
```

## Recruiter Disclaimer
Use this disclaimer in README or portfolio:

> UBank Digital is a Figma UI/UX prototype created for portfolio presentation. It does not process real transactions, store banking data, connect to banking APIs, or include backend infrastructure.

## Final Security Acceptance Criteria
Project is safe to publish when:

- [ ] No sensitive-looking data is visible
- [ ] No full card number is shown
- [ ] No CVV is shown
- [ ] No real email or phone number is shown
- [ ] Figma permission is view-only
- [ ] Video does not reveal private data
- [ ] Screenshots are exported from cleaned frames
- [ ] Portfolio copy does not overclaim functionality
- [ ] README clearly states this is a UI/UX prototype
