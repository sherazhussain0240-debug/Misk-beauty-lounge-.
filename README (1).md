# MISK BEAUTY LOUNGE

A responsive multi-page static website for Netlify and Vercel.

## Pages
- `index.html` — Home
- `services.html` — Service descriptions
- `pricing.html` — Price guide
- `gallery.html` — Image gallery and video
- `about.html` — About the lounge
- `booking.html` — Appointment request form
- `contact.html` — Contact form
- `privacy.html` — Privacy policy

## Deploy on Netlify
1. Extract this ZIP.
2. Open Netlify and choose **Add new site → Deploy manually**.
3. Drag the extracted project folder (the folder containing `index.html`) into the deploy area.

## Deploy on Vercel
1. Extract this ZIP and upload the project to a GitHub repository.
2. In Vercel choose **Add New → Project** and import the repository.
3. Framework preset: **Other**. Build command: leave blank. Output directory: `.`.
4. Deploy.

No build step, npm install, or framework setup is required.

## Before publishing
- Prices are sample starting rates. Replace them with your actual approved prices.
- Replace social profile links with your official pages.
- Add your real salon address and opening hours to Contact.
- Photos, Google Fonts and the demo video are loaded from external URLs and need an internet connection.
- Booking/contact forms open WhatsApp with a prefilled message. The visitor must press Send in WhatsApp. This static site does not store submissions or send email.
- The phone number shown is `03259567575`; the WhatsApp link uses the international Pakistan format `923259567575`.

## Customization
- Edit content in the HTML pages.
- Change colors and layout in `assets/style.css`.
- Change interactions and WhatsApp form behavior in `assets/app.js`.
