# Primark Tools Portal

A central access point for PACD and Primark operational tools. The portal provides a clean, responsive interface for opening approved calculators, reports, and registration services.

## Features

- Corporate white and navy visual design
- Responsive layout for desktop and mobile devices
- Accessible navigation and keyboard focus states
- External tools open securely in a new browser tab
- Automatically updated copyright year

## Available Tools

| Tool | Destination |
| --- | --- |
| Carton Price Calculator | <https://primark.pac-d.com/carton-price-calculator> |
| Carton Supply Report | <https://primark.pac-d.com/carton-supply-report> |
| Event Registration | <https://registration.pac-d.com> |

## Project Structure

```text
primark-portal/
├── assets/          Brand images and favicon
├── css/             Website styles
├── js/              Client-side functionality
├── index.html       Main portal page
└── README.md        Project documentation
```

## Local Use

Open `index.html` in a modern web browser. No build process or package installation is required.

## Deployment

The project is a static website and can be deployed through GitHub Pages or any standard static hosting provider. Publish the contents of the project directory without modification.

## Maintenance

- Update destination URLs in `index.html`.
- Update presentation rules in `css/styles.css`.
- Keep logos and brand assets inside the `assets` directory.

## Development

Developed by [recurSID](https://github.com/recursid).
