# Feedback Docs

Feedback management documentation built with [Mintlify](https://mintlify.com/).

## Prerequisites

- **Node.js** (v18 or higher) — [Download here](https://nodejs.org/)
- **npm** (comes with Node.js)

## Installation

Install the Mintlify CLI globally:

```bash
npm install -g mintlify
```

> **Windows users:** If you get an EACCES error, run your terminal as Administrator or configure npm to use a different directory.

## Running Locally

1. Clone the repository and navigate into the project folder:

```bash
cd Feedback-doc
```

2. Start the development server:

```bash
mintlify dev
```

3. Open the URL shown in your terminal (usually `http://localhost:3000`) in your browser.

## Platform-Specific Setup

### Windows

1. Install Node.js from the [official website](https://nodejs.org/) (LTS version recommended).
2. Open **Command Prompt** or **PowerShell** as Administrator and run:
   ```bash
   npm install -g mintlify
   ```
3. In the project directory run:
   ```bash
   mintlify dev
   ```
4. Open `http://localhost:3000` in your browser (Edge, Chrome, etc.).

### iOS (macOS)

> **Note:** iOS development requires a Mac. The steps below are for macOS. Once the server is running, you can preview the site on an iOS device using Safari.

1. Install Node.js from the [official website](https://nodejs.org/) (LTS version recommended) or via Homebrew:
   ```bash
   brew install node
   ```
2. Install the Mintlify CLI:
   ```bash
   npm install -g mintlify
   ```
3. In the project directory run:
   ```bash
   mintlify dev
   ```
4. To view on your **iPhone or iPad**:
   - Make sure your iOS device is on the **same Wi-Fi network** as your Mac.
   - Find your Mac's local IP address (System Settings → Network → Wi-Fi → Details).
   - On your iOS device, open Safari and go to `http://<your-mac-ip>:3000`.

## Building for Production

To generate a static production build:

```bash
mintlify build
```

The output will be in the `dist/` folder (or as configured by Mintlify).

## Useful Links

- [Mintlify Documentation](https://mintlify.com/docs)
- [MDX Syntax](https://mdxjs.com/)
