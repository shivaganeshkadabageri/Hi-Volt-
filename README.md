# Hi-Volt Engineering Solutions Website

A responsive, interactive business website for **Hi-Volt Engineering Solutions**, a Bangalore-based manufacturer and supplier of high-voltage testing and measuring equipment. The website showcases the company's products, background, quality policy, customers, and contact information.

## 🚀 Features

- **Home Page:** Introduction to the company with navigation and contact information.
- **About Us:** Company background, establishment details, and industry standards.
- **Products:** Displays high-voltage testing and measuring equipment with specifications and descriptions.
- **Product Enquiries:** Allows visitors to enquire about specific products.
- **Gallery:** Image gallery with category-based filtering and an image viewer.
- **Customers:** Displays customer names and supports customer logo uploads.
- **Quality Policy:** Presents quality objectives and the company's commitment to product quality.
- **Contact Section:** Provides contact details, email, phone, WhatsApp, and Google Maps directions.
- **Enquiry Form:** Allows visitors to prepare enquiries through email or WhatsApp.
- **Admin Edit Mode:** Password-protected browser-based editing for website content, products, gallery images, and customer information.
- **Image Management:** Upload, resize, and compress images.
- **Import and Export:** Export website content as JSON and import previously exported content.
- **Local Data Storage:** Saves changes in the browser using IndexedDB and localStorage.
- **Responsive Design:** Adapts to different screen sizes.
- **Dark Mode Support:** Supports the system's preferred color scheme and manual theme configuration.
- **Accessibility Enhancements:** Includes keyboard focus indicators, accessible labels, and reduced-motion support.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JavaScript)
- IndexedDB
- localStorage
- HTML Forms and Browser APIs
- Google Maps, Gmail, and WhatsApp links

## 📂 Project Structure

```text
Hi-Volt-Engineering-Solutions/
│
├── index.html       # Complete website application
└── README.md        # Project documentation
```

The application is implemented in a single HTML file containing the page structure, styles, JavaScript functionality, and default website content.

## ⚙️ How to Run the Project

### Prerequisites

- A modern web browser such as Google Chrome, Microsoft Edge, or Firefox.
- Visual Studio Code (recommended for editing the source code).

### Steps

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   ```

2. Open the project folder:

   ```bash
   cd <YOUR_PROJECT_FOLDER>
   ```

3. Open the folder in Visual Studio Code.

4. Open `index.html` in your browser.

   Alternatively, install the **Live Server** extension in VS Code, right-click `index.html`, and select **Open with Live Server**.

No package installation or backend server is required for the basic website functionality.

## 📦 Products Showcased

The website includes the following product categories:

- Modular High Voltage Test Systems
- AC Test Transformers
- Impulse Generators
- Partial Discharge Meters and Kits
- Impulse Resistors and Inductors
- Shunts for High Current Measurement

Additional equipment includes high-voltage AC/DC test sets, measuring and coupling capacitors, measuring spark gaps, and other specialized testing equipment.

## ✏️ Website Content Management

The website includes a browser-based Edit Mode.

1. Open the website.
2. Click the lock icon in the footer.
3. Enter the configured owner password.
4. Edit supported text fields or manage products, gallery images, and customer entries.
5. Click **Save** to store the changes in the browser.
6. Use **Export JSON** to download the updated website content.
7. Use **Import JSON** to restore previously exported content.

**Important:** Changes saved in the browser are not automatically published to GitHub or shared with other visitors. To publish updated default content, update the `DEFAULT` configuration in `index.html` with the exported JSON data and redeploy the website.

## 📬 Contact Information

**Hi-Volt Engineering Solutions**

- **Email:** marketing@hivoltengineeringsolutions.com
- **Phone:** +91 99860 24480 / +91 98800 89509
- **Location:** Bengaluru, Karnataka, India

For additional information, product specifications, or enquiries, please use the contact details provided on the website.

## 🔒 Security Notes

- The current Edit Mode password is stored in the client-side JavaScript configuration. It is intended only as a basic editing restriction and **is not secure authentication**.
- Do not store confidential information or sensitive credentials in client-side code.
- For production use, implement server-side authentication and authorization if administrative access must be protected.
- The enquiry form uses email-draft links by default. To process enquiries through a form service, configure the appropriate Formspree endpoint in the application.
- Contact and third-party links require an internet connection.

## 🌐 Deployment

The website can be deployed using static hosting platforms such as:

- GitHub Pages
- Netlify
- Vercel

Upload or push the project files to your GitHub repository and configure your preferred hosting provider to publish `index.html`.

## 📄 License

This project is intended for the Hi-Volt Engineering Solutions website. Add an appropriate license if you plan to distribute or reuse the source code publicly.

---

**Developed using HTML, CSS, and JavaScript.**
