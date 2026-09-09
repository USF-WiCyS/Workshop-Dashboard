# Anatomy of a Business IT Ecosystem Explorer

An interactive, beginner-friendly learning tool for exploring how a business IT environment fits together—and the kinds of data its systems produce.

The Explorer is designed for students, aspiring IT and cybersecurity professionals, and anyone who wants a practical way to understand enterprise infrastructure. Rather than treating servers, identity systems, cloud services, endpoints, networks, and security tools as isolated topics, it presents them as one connected ecosystem.

## What you can learn

Use the Explorer to become familiar with:

- Common parts of a business IT environment, including endpoints, servers, network devices, identity services, cloud services, applications, and security tooling
- How systems exchange information and depend on one another
- The telemetry and records systems can generate, such as authentication logs, endpoint activity, network events, cloud audit events, application logs, alerts, and asset data
- Where IT, security operations, incident response, and threat-hunting teams gain visibility
- Why collecting, correlating, and retaining data matters during troubleshooting and security investigations

## Who it is for

This project is intended for:

- Cybersecurity and IT students
- Beginners learning enterprise infrastructure concepts
- Workshop participants and instructors
- SOC, incident-response, and threat-hunting learners who want to connect telemetry to its source systems
- Anyone who learns best by exploring an interactive visual model

No prior technical experience is required. You can start by selecting a component, reading its description, and following the connections between systems.

## Getting started

You can use the Explorer in either of two ways.

### Option 1: Use the hosted GitHub Pages site

Open the project’s GitHub Pages link provided by the project maintainer. The tool runs in a modern web browser; no installation, account, or configuration is required.

For the best experience, use a current version of Chrome, Edge, Firefox, or Safari on a desktop or laptop.

### Option 2: Download the project

1. Open the repository on GitHub.
2. Select **Code**.
3. Select **Download ZIP**.
4. Extract the downloaded ZIP file.
5. Open `Anatomy-of-a-Business-IT-Ecosystem-Explorer.html` in a modern web browser.

The Explorer is a self-contained HTML experience, so it can be opened locally after downloading it.

### Option 3: Clone the repository

If you use Git, clone the repository locally:

```bash
git clone <repository-url>
cd <repository-folder>
```

Then open `Anatomy-of-a-Business-IT-Ecosystem-Explorer.html` in your browser.

> Replace `<repository-url>` and `<repository-folder>` with the actual repository information.

## How to use the Explorer

1. Enter your name when prompted so that any notes you create are labeled.
2. Start with a familiar area, such as employee devices, email, identity, cloud services, or the corporate network.
3. Select a component on the map to view what it does and how it participates in the broader environment.
4. Review the data and telemetry associated with that component.
5. Follow the visual relationships to see which systems communicate with, manage, protect, or monitor one another.
6. Compare the data source to a real-world question, such as: “Where would a security analyst look for evidence of a suspicious sign-in?”
7. Add observations or notes as you explore, if that feature is enabled in your version of the tool.
