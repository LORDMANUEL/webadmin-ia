# WebAdmin AI Dashboard

This is a simple, single-page web dashboard for managing web servers, databases, and AI-powered services. The dashboard provides a clean, modern interface for monitoring resource consumption and managing various aspects of a web hosting environment.

## Features

*   **Resource Monitoring:** View real-time usage of RAM, CPU, SSD, and Ethernet.
*   **Website Management:** Add, view, edit, and download websites.
*   **Database Management:** Manage databases, including creating backups and running queries.
*   **AI Services:** Monitor the status of AI models (RAG and Finetuning) and generate AI-powered pages.
*   **Workflow Automation:** View and manage automated workflows for tasks like backups and deployments.
*   **Light and Dark Modes:** The dashboard supports both light and dark color schemes.

## How to Use

1.  Clone this repository to your local machine.
2.  Open the `index.html` file in your web browser.

No special setup or dependencies are required to view the dashboard. All styles and scripts are loaded from a CDN.

## File Structure

*   `index.html`: The main HTML file containing the dashboard's structure, styling, and JavaScript.

## Customization

You can customize the dashboard by editing the `index.html` file. The styles are defined using Tailwind CSS, and the configuration is included in a `<script>` tag in the `<head>` of the document. The JavaScript code for updating the time is also located in a `<script>` tag at the end of the `<body>`.
