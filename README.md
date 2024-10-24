Ape-x Anti-Phishing Browser Extension
Ape-x is a browser extension designed to detect and block dangerous websites that attempt to collect user data illegally. It not only alerts users when they visit phishing or malicious websites, but also provides an option to delete any personal data stored by such sites. Built with HTML, CSS, and JavaScript, this extension aims to enhance web security and protect users' privacy.

Features
Real-time Phishing Detection: Actively monitors websites for suspicious activity and alerts users when they attempt to visit a known or suspected phishing site.
Data Deletion Mechanism: Allows users to delete all personal data that a website may have collected.
User Alerts: Provides clear and instant warnings with a pop-up notification when visiting dangerous websites.
Lightweight and Fast: Built with simple, efficient code to ensure minimal impact on browser performance.
Customizable Settings: Users can configure the extension to block specific websites or automatically delete data upon detection.
How It Works
Website Scanning: Ape-x scans websites in real-time to identify phishing indicators based on a database of known threats and specific characteristics of malicious sites.
Data Removal: If a website is flagged as dangerous, the extension offers an option to delete cookies, form data, and other local storage related to the site, protecting the user’s privacy.
Alerts: A pop-up notification informs the user when they encounter a potentially harmful website and gives them the option to proceed, block the site, or delete any stored data.
Installation
Clone or download this repository:

bash

git clone https://github.com/known-27/Ape-x.git
cd Ape-x
Load the extension in your browser:

For Chrome:
Open chrome://extensions/.
Enable Developer Mode.
Click Load unpacked and select the folder containing the extension files.
For Firefox:
Open about:debugging.
Click This Firefox.
Click Load Temporary Add-on, then select the manifest.json file in the extension folder.
Activate the extension and start browsing safely with real-time phishing detection.

Folder Structure
bash

├── css/
│   ├── style.css             # Styles for the extension UI
├── js/
│   ├── background.js         # Core logic for phishing detection and data deletion
│   ├── popup.js              # Handles user interactions through the extension’s popup
├── popup.html                # UI for the extension's alert and data deletion options
├── manifest.json             # Extension manifest for browser configuration
Technologies Used
HTML: Structure and layout for the extension's user interface.
CSS: Styling for a clean and user-friendly design.
JavaScript: Core functionality, including phishing detection, data deletion, and user interaction.
How to Contribute
Fork the repository.
Create a new branch:
bash

git checkout -b feature-new-feature
Make your changes and commit:
bash

git commit -m "Add new feature"
Push to your branch:
bash

git push origin feature-new-feature
Open a pull request and describe your changes.
