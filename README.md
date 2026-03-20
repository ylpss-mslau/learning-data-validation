# Data Validation Learning Tool

An interactive, bilingual web application designed for Information and Communication Technology (ICT) students to understand the concepts of Data Validation and Error Prevention.

[Learning Data Validation](https://charlotte-lau-hk.github.io/learning-data-validation/)

(Created with Google Gemini)

## 🌟 Features

* **Interactive Rule Testing:** Students can type into a test field and instantly see if their input passes or fails various validation rules.
* **Customizable Rules:** Toggle and configure different validation checks in real-time:
  * **Presence Check:** Prevents empty inputs.
  * **Length Check:** Restricts character count (greater than, less than, exactly).
  * **Range Check:** Ensures numerical inputs fall within a specific boundary.
  * **Type Check:** Restricts input to integers, non-digits, or complex passwords.
  * **Format Check:** Enforces specific patterns like emails (`@`) or dates (`YYYY-MM-DD`).
* **UI Error Prevention Showcase:** A dedicated section demonstrating how smart UI controls (Dropdowns, Sliders, Date Pickers) can prevent invalid data entry before it even happens.
* **Bilingual Support:** Fully translates between English and Traditional Chinese (中文) at the click of a button.
* **Zero Dependencies:** Built entirely with Vanilla Web technologies. No Node.js, npm, or build steps required.

## 🛠️ Tech Stack

* **HTML5 & Vanilla JavaScript:** Pure client-side logic.
* **Tailwind CSS (via CDN):** For modern, responsive, and clean styling.
* **Lucide Icons (SVG):** Embedded directly for a lightweight footprint.

## 🚀 How to Run Locally

Because this project uses vanilla web technologies, running it is incredibly simple:

1. Clone or download this repository.
2. Double-click the `index.html` file to open it in any modern web browser (Chrome, Edge, Safari, Firefox).
3. That's it! No local server or installation required.

## 🌐 Hosting on GitHub Pages

Since this is a static, single-file application, it is perfect for free hosting via GitHub Pages.

1. Upload `index.html` to the root of your GitHub repository.
2. In your repository, go to **Settings**.
3. On the left sidebar, click on **Pages**.
4. Under "Build and deployment", set the **Source** to `Deploy from a branch`.
5. Under **Branch**, select `main` (or `master`) and leave the folder as `/ (root)`.
6. Click **Save**.
7. Wait a minute or two, and GitHub will provide you with a live URL to share with your students!

## 🤝 Contributing

Feel free to fork this project, submit pull requests, or open issues if you'd like to add more validation rules or UI examples!

## 📄 License

This project is open-source and available under the MIT License.
