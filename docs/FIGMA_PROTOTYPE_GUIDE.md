# Figma Prototype Guide — UBank Digital

## Purpose
File ini menjelaskan cara menampilkan Figma prototype UBank Digital secara rapi untuk recruiter, CV, GitHub, dan website portfolio.

## Available Figma Links
Gunakan link prototype sebagai primary demo:

```text
https://www.figma.com/proto/lVhdA8v8ZryFdV85kppDs7/UBank-APP?node-id=1-2&t=6EAQY3SrkG1Z8THl-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A2
```

Jika ingin menyertakan design file:

```text
https://www.figma.com/design/lVhdA8v8ZryFdV85kppDs7/UBank-APP?node-id=0-1&p=f&t=54wpuTtAaHUYEy24-0
```

## Recommended Public Sharing Settings
Sebelum dibagikan ke recruiter:

- Set prototype permission ke "Anyone with the link can view"
- Pastikan prototype starting point mengarah ke splash/onboarding
- Pastikan tidak ada data pribadi atau sensitif yang tampil
- Pastikan frame order sudah rapi
- Pastikan semua hotspot utama bekerja
- Pastikan file yang dibagikan adalah versi portfolio-clean, bukan versi internal/raw

## Prototype Flow To Highlight
Flow yang sebaiknya ditunjukkan:

```text
Splash
→ Onboarding
→ Sign In / Register
→ Home Dashboard
→ Statistics
→ My Cards
→ Transaction History
→ Search Transaction
→ Send Money
→ Profile / Settings
```

## Recommended Embed Usage
Untuk website portfolio, gunakan embed Figma hanya jika:

- Halaman tidak menjadi terlalu berat
- Prototype dapat dilihat di desktop dan mobile
- Link fallback tetap tersedia
- Recruiter tetap bisa membuka langsung di Figma

CTA fallback:

```markdown
[Open Figma Prototype](PASTE_PROTOTYPE_LINK_HERE)
```

## Figma Cleanup Before Sharing
Checklist:

- [ ] Duplicate original Figma file before editing
- [ ] Fix obvious typos
- [ ] Mask card numbers
- [ ] Mask CVV
- [ ] Mask phone number
- [ ] Mask email if needed
- [ ] Standardize currency format
- [ ] Standardize language
- [ ] Remove inconsistent or unfinished screens from main presentation
- [ ] Re-check prototype hotspots
- [ ] Set clear starting frame
- [ ] Rename frames using readable names

## Recommended Frame Naming
Gunakan format berikut:

```text
01 Splash
02 Onboarding - Fast Payment
03 Onboarding - Security
04 Onboarding - Convenience
05 Sign In
06 Register
07 Home Dashboard
08 Statistics
09 My Cards
10 Settings
11 Profile
12 Edit Profile
13 Add New Card
14 All Cards
15 Transaction History
16 Search Transaction
17 Category Chart
18 Send Money - Recipient
19 Send Money - Detail
20 Language
21 Change Password
22 Terms and Conditions
```

## Notes For Portfolio
Tulis dengan jelas:

> This project is a Figma UI/UX prototype and design exploration for a mobile banking experience. It does not include backend integration or real banking functionality.
