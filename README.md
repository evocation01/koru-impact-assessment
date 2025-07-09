# koru-impact-assessment

A repo for the Koru Impact Foundational Tech Assessment

This project is the technical assessment for the Foundational Technologist role at Koru Impact. It is a production-ready, multi-page static website built to serve as the company's "digital front door" and meet the verification standards for programs like the Google for Startups Cloud Program.

The entire project was architected and built according to the detailed project brief, focusing on technical soundness, professional design, and brand-aligned content.

---

## 🚀 Live Demo

A live, deployed version of the website can be viewed here:

https://koru-impact-website.netlify.app

---

## ✅ Core Requirements Checklist

This website was built to fulfill all criteria from the project brief's Verification Checklist:

- **✅ Professional Domain & Email:** A legitimate company email is provided on the Contact page.
- **✅ Clear Value Proposition:** The homepage hero section immediately communicates Koru Impact's core mission.
- **✅ Content-Rich & Informative:** The site includes four dedicated pages (Home, About, Services, Contact) with substantial, well-written content.
- **✅ Professional & Clean Design:** The aesthetic is modern, minimalist, and trustworthy, strictly adhering to the specified color palette and typography.
- **✅ Technical Soundness:** The site is fully responsive, loads quickly, and is deployed securely on a modern hosting platform.
- **✅ Clear Call-to-Action (CTAs):** Each page guides the user toward a logical next step, from discovery to contact.
- **✅ Credibility & Trust Signals:** The founder's professional bio and the company's detailed mission are included to build trust.

---

## 🛠️ Tech Stack

- **HTML5:** For clean, semantic, and accessible structure.
- **Tailwind CSS (v3 via Play CDN):** For rapid, utility-first styling and a fully responsive layout. The specified brand colors and fonts were integrated into the Tailwind configuration.
- **Google Fonts:** `Lato` for headings and `Libre Baskerville` for body text were imported to match the brand guidelines.
- **AI-Assisted Content Generation:** All written copy was generated using an LLM prompted with the "Sage-Caregiver-Hero" brand archetype and the source material from the appendices, as per the AI Content Generation Strategy.

---

## 🚀 Deployment

The website is deployed via a continuous integration pipeline:

1.  **Version Control:** The code is hosted on this GitHub repository.
2.  **Hosting:** The repository is connected to **Netlify**.
3.  **Continuous Deployment:** Every push to the `main` branch automatically triggers a new deployment, ensuring the live site is always up-to-date.

---

## local-dev How to Run Locally

No complex build steps are required.

1.  Clone this repository:
    ```sh
    git clone https://github.com/your-username/koru-impact-website.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd koru-impact-website
    ```
3.  Open any of the `.html` files (e.g., `index.html`) in your web browser.
