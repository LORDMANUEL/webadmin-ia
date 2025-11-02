# WebAdmin AI Dashboard

Welcome to the WebAdmin AI Dashboard, a modern, single-page web interface for managing servers, databases, and AI-powered services. This dashboard features a clean, visually appealing **Neumorphic design** with both light and dark modes, providing an intuitive user experience for monitoring and managing your web hosting environment.

## Preview
*A preview of the new Neumorphic design will be added here shortly.*

## Key Features

*   **Neumorphic Design:** A modern and stylish interface with a soft, extruded plastic look.
*   **Dynamic Light/Dark Theme:** Seamlessly switch between light and dark modes to suit your preference.
*   **At-a-Glance Stats:** Four prominent cards display key metrics: Active Websites, Databases, Workflows, and Active Users.
*   **Subtle Animations:** Smooth, subtle animations on interactive elements enhance the user experience.
*   **Resource Monitoring:** Keep an eye on real-time usage of RAM, CPU, SSD, and Ethernet.
*   **Website Management:** Easily add, view, edit, and download your websites.
*   **Database Control:** Manage your databases with tools for backups, queries, and more.
*   **AI Service Integration:** Monitor the status of your AI models (RAG and Finetuning) and generate AI-powered web pages.
*   **Workflow Automation:** View and manage automated workflows for tasks like backups and deployments.
*   **Multi-language Support:** The dashboard is available in both English and Spanish.

## How to Use

1.  Clone this repository to your local machine.
2.  Open the `index.html` file in your web browser.

No special setup or dependencies are required. All necessary styles and scripts are loaded from a CDN.

## File Structure

*   `index.html`: The main HTML file containing the dashboard's structure, styling, and all JavaScript logic.
*   `README.md`: This file, providing an overview of the project.
*   `images/`: Directory intended for storing image assets, like the dashboard preview.

## Customization

You can easily customize the dashboard by editing the `index.html` file.

*   **Styling:** The dashboard uses **Tailwind CSS**. The configuration is located in a `<script>` tag in the `<head>` of the document. You can modify this to change colors, fonts, and other visual elements.
*   **Functionality:** All JavaScript, including the theme-switching and multi-language logic, is contained within a `<script>` tag at the end of the `<body>`.
*   **Multi-language Support:** To add a new language, you'll need to:
    1.  Add a new language option to the language selector dropdown in the header.
    2.  Add a new set of translations to the `translations` object in the JavaScript code.
    3.  Use the `data-translate` attribute on any HTML elements that require translation.
