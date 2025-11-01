# WebAdmin AI Dashboard

This is a simple, single-page web dashboard for managing web servers, databases, and AI-powered services. The dashboard provides a clean, modern interface for monitoring resource consumption and managing various aspects of a web hosting environment.

## Preview
![Dashboard Preview](images/screenshot.png)

## Features

*   **Resource Monitoring:** View real-time usage of RAM, CPU, SSD, and Ethernet.
*   **Website Management:** Add, view, edit, and download websites.
*   **Database Management:** Manage databases, including creating backups and running queries.
*   **AI Services:** Monitor the status of AI models (RAG and Finetuning) and generate AI-powered pages.
*   **Workflow Automation:** View and manage automated workflows for tasks like backups and deployments.
*   **Light and Dark Modes:** The dashboard supports both light and dark color schemes.
*   **Multi-language Support:** The dashboard is available in English and Spanish.

## How to Use

1.  Clone this repository to your local machine.
2.  Open the `index.html` file in your web browser.

No special setup or dependencies are required to view the dashboard. All styles and scripts are loaded from a CDN.

## File Structure

*   `index.html`: The main HTML file containing the dashboard's structure, styling, and JavaScript.
*   `images/`: Directory containing images used in the dashboard.

## Customization

You can customize the dashboard by editing the `index.html` file. The styles are defined using Tailwind CSS, and the configuration is included in a `<script>` tag in the `<head>` of the document. The JavaScript code for updating the time is also located in a `<script>` tag at the end of the `<body>`.

### Multi-language Support

The multi-language support is implemented using a JavaScript function that replaces the text of elements with the `data-translate` attribute. The translations are stored in a JavaScript object in the `index.html` file. To add a new language, you need to:

1.  Add a new language option to the language selector in the header.
2.  Add a new set of translations to the `translations` object in the JavaScript code.
3.  Add the `data-translate` attribute to the HTML elements that need to be translated.
