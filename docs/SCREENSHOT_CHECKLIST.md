# Screenshot Checklist — UBank Digital

## Purpose
Screenshot digunakan untuk portfolio website, CV attachment, GitHub README, Behance/Dribbble preview, dan case study.

## Export Standard
Recommended export setting:

- Format: PNG
- Scale: 2x
- Background: visible
- Frame naming: lowercase, numbered
- Avoid cropping important UI
- Use consistent mockup if needed

## Required Screenshots
Export screen berikut untuk portfolio utama:

```text
01-splash-logo.png
02-onboarding-fast-payment.png
03-onboarding-security.png
04-onboarding-convenience.png
05-sign-in.png
06-register.png
07-home-dashboard.png
08-statistics.png
09-my-cards.png
10-settings.png
11-profile.png
14-all-cards.png
15-transaction-history.png
16-search-transaction.png
18-send-money-recipient.png
19-send-money-detail.png
```

## Optional Screenshots
Gunakan jika sudah dirapikan:

```text
12-edit-profile.png
13-add-new-card.png
17-category-chart.png
20-language.png
21-change-password.png
22-terms-and-conditions.png
```

## Hero Screenshot Recommendation
Gunakan 3–5 screen berikut sebagai hero visual:

1. Home Dashboard
2. My Cards
3. Transaction History
4. Send Money
5. Onboarding

## Gallery Grouping
Susun screenshot di portfolio berdasarkan kategori:

### Onboarding
- Splash
- Onboarding 1
- Onboarding 2
- Onboarding 3

### Authentication
- Sign in
- Register

### Main Banking Experience
- Home dashboard
- Statistics
- My cards
- All cards

### Transactions
- Transaction history
- Search transaction
- Send money
- Payment detail

### Account Management
- Profile
- Settings
- Language
- Change password

## Cleanup Before Export
- [ ] Fix obvious typos
- [ ] Mask card number
- [ ] Mask CVV
- [ ] Mask email
- [ ] Mask phone number
- [ ] Use consistent currency format
- [ ] Use consistent language
- [ ] Check button alignment
- [ ] Check spacing consistency
- [ ] Check font hierarchy
- [ ] Remove irrelevant prototype UI if exporting from preview
- [ ] Confirm all exported screenshots are sharp

## Data Masking Examples
Use:

```text
Card Number: 1234 **** **** 1121
CVV: ***
Email: user@example.com
Phone: +62 812 **** ****
Balance: Rp 12.000.000
```

Avoid:

```text
Full card number
Visible CVV
Real phone number
Real email
Personal date of birth
Real address
```

## Recommended Folder Structure
```text
/screenshots
  /hero
  /onboarding
  /auth
  /dashboard
  /cards
  /transactions
  /settings
```
