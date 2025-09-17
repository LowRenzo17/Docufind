 Project Overview

DocuFind is a web application designed to help people report, search, and recover lost important documents such as ID cards, passports, driver's licenses, and certificates. The platform provides a secure way to connect document finders with owners while protecting privacy through verification processes.
This  project just need the support of backend you can reach outthrough lorenzorenzo1738@gmail.com or 254713398446
✨ Features

    Document Reporting: Users can report both lost and found documents

    Advanced Search: Search documents by type, name, location, or date

    Interactive Map: Visual representation of where documents were found

    User Authentication: Secure login/registration system

    Responsive Design: Works seamlessly on mobile and desktop devices

    Privacy Protection: Partial information display until verification

    Admin Panel: For managing documents and users (backend required)

🛠️ Technology Stack

    Frontend: HTML5, CSS3, JavaScript (ES6+)

    Mapping: Leaflet.js with OpenStreetMap

    Icons: Font Awesome

    Backend: Node.js, Express.js, MongoDB -later on after learning the backend 

    Deployment: GitHub Pages, 
📁 Project Structure
text

docufind-website/
├── index.html          # Main HTML file
├── style.css          # All CSS styles
├── script.js           # All JavaScript functionality
├── README.md           # This file

🚀 Installation & Setup
Prerequisites

    A modern web browser (Chrome, Firefox, Safari, Edge)

    A code editor (VS Code recommended)

    Git for version control

Local Development

    Clone the repository:
    bash

git clone https://github.com/LowRenzo17/Docufind.git

Open the project in your code editor

Launch the website:

    Option 1: Open index.html directly in your browser

    Option 2: Use a local server (recommended):
    bash


📱 Usage Guide
For Users Who Lost Documents:

    Click "Report Document" from the homepage

    Select "Lost Document" option

    Fill in document details and your contact information

    Submit the report

    Use the search feature to check for matches

    Claim documents when found and complete verification

For Users Who Found Documents:

    Click "Report Document" from the homepage

    Select "Found Document" option

    Fill in document details and location found

    Submit the report

    Respond to verification requests from potential owners

Searching for Documents:

    Use the search page to filter by document type, name, or location

    Browse results or use the interactive map

    Click "View Details" for more information

    Claim documents that might be yours


Adding Document Types

Edit the select options in both HTML and JavaScript files:
html

<option value="new-type">New Document Type</option>

Modifying Map Settings

Adjust the map initialization in script.js:
javascript

// Change default coordinates and zoom level
map.setView([your-lat, your-lng], your-zoom-level);


🤝 Contributing

We welcome contributions to DocuFind! Please follow these steps:

    Fork the project

    Create a feature branch (git checkout -b feature/amazing-feature)

    Commit your changes (git commit -m 'Add amazing feature')

    Push to the branch (git push origin feature/amazing-feature)

    Open a Pull Request

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
🆘 Support

If you need help with DocuFind:

    Check the FAQ section on the website

    Open an issue on GitHub for bugs or feature requests

    Contact support at lorenzorenzo@gmail.com

🙏 Acknowledgments

    Leaflet.js for the mapping functionality

    Font Awesome for the icons

    OpenStreetMap for map data

 
