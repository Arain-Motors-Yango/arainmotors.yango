# Araim Motors | Rider Recruitment Website

A responsive, mobile-friendly landing page for **Araim Motors**, designed to introduce the rider recruitment process, explain the application steps, answer common questions, and help interested applicants contact the team.

> **Important:** This repository contains an independent recruitment website. Do not describe it as an official Yango website or imply a partnership, endorsement, or authorization unless that status has been confirmed and the relevant brand permissions are in place.

## ✨ Features

- Responsive layout for desktop, tablet, and mobile screens
- Clean, high-contrast visual design and Araim Motors branding with a red Yango logo display
- Sections for the homepage, company introduction, opportunities, application steps, FAQs, and contact details
- Rider interest form with fields for contact details, city, licence status, vehicle availability, experience, and preferred contact method
- Basic form validation, applicant consent checkbox, and hidden honeypot spam field
- Web3Forms integration that sends rider applications to the email address configured for the supplied access key
- Submission progress, success, and error feedback
- Semantic HTML and lightweight, dependency-free front-end

## 🧰 Built With

- HTML5
- CSS3
- Vanilla JavaScript

No package installation or build step is required for the current static website.

## 🚀 Run Locally

1. Clone or download this repository.
   ```bash
   git clone https://github.com/Arain-Motors-Yango/arainmotors.yango.git
   ```
2. Open the project folder.
3. Open `index.html` in a modern browser.

For a local development server, you can use the Live Server extension in Visual Studio Code.

## 🌐 Deploy with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under the build and deployment settings, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.
5. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages settings.

GitHub Pages deployment must be enabled by a repository administrator. A custom domain can be configured in the same settings if you own the domain.

## 📩 Application Form: Web3Forms

The rider interest form submits to the Web3Forms API (`https://api.web3forms.com/submit`) and displays success or error feedback. The Web3Forms access key is a public form identifier, not a private API secret, and is intended to be present in client-side HTML. It can be used by others to attempt submissions, so keep spam controls enabled and verify the configured recipient inside your Web3Forms account. If your plan supports it, restrict submissions to the published website domain; a CAPTCHA such as Turnstile or hCaptcha can add another anti-spam layer.

The form includes a hidden honeypot field, but no client-side spam measure guarantees that all spam will be blocked. Review Web3Forms spam-protection options and consider domain restrictions if available for your plan. Test a submission end-to-end before publishing the site.

The website collects contact and recruitment enquiry information. Publish a clear privacy notice, limit collection to information you need, and avoid requesting identity-document numbers or other sensitive information through this initial form. Review the service's current terms and data-retention details before launch.

## ⚙️ Customization

- **Website content and layout:** edit `index.html`.
- **Contact destination:** Manage and verify the recipient address inside the Web3Forms account for this form. Keep private inbox addresses out of public site content and repository documentation.
- **Brand asset:** the header and footer use the original red Arain Motors logo at `assets/arain-motors-logo.svg`. Keep the visual identity consistent and only use third-party trademarks/assets when authorized.
- **Recruitment terms:** verify eligibility criteria, fees (if any), required documents, and any claims about earnings or opportunities before publishing them.
- **Privacy and legal text:** adapt it to the actual application workflow and applicable local requirements.

## ✅ Before Launch

- [ ] Verify the contact email address.
- [ ] Test all navigation links and form fields on mobile and desktop.
- [ ] Confirm recruitment information and eligibility requirements are accurate.
- [ ] Verify the recipient email configured for the Web3Forms access key.
- [ ] Send a test application and confirm it arrives in the intended inbox.
- [ ] Review Web3Forms spam-protection and domain restriction settings.
- [ ] Publish a privacy notice that accurately explains what applicant information is collected and how it is used.
- [ ] Confirm permission for any third-party names, logos, or partnership claims.
- [ ] Enable GitHub Pages or configure another hosting provider.

## 📁 Project Structure

```text
arainmotors.yango/
├── index.html
├── about.html
├── opportunities.html
├── driver-guide.html
├── how-it-works.html
├── faq.html
├── join.html
├── report-problem.html
├── before-you-apply.html
├── enquiry-process.html
├── contact.html
├── assets/
│   └── arain-motors-logo.svg
├── robots.txt
├── sitemap.xml
└── README.md
```

## 🤝 Contributing

For changes, create a branch, make and test your updates, then open a pull request describing what changed.

## 📄 License

No open-source license has been specified yet. Unless a license is added, do not assume that the repository's contents may be reused, redistributed, or modified by others.

---

**Maintained by Araim Motors.**
