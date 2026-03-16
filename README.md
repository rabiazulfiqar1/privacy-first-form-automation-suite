# Privacy-First Form Automation Suite

A Chrome extension for automated web form testing with encrypted storage, PostgreSQL-backed analytics, and React-based admin interface. Features dynamic field mapping and AI-powered form pattern recognition.

## Features

- **Chrome Extension**: Automate web form testing with dynamic field mapping
- **Encrypted Storage**: Securely store form profiles using encryption
- **AI-Powered Form Recognition**: Identify and map form fields automatically
- **PostgreSQL Analytics**: Track and analyze form testing metrics
- **React Admin Dashboard**: Monitor and manage automation through a modern UI

## Tech Stack

- **JavaScript/TypeScript**: Core language for extension and logic
- **React**: Admin dashboard UI
- **PostgreSQL**: Analytics and data storage
- **Chrome Extension APIs**: Background scripts and content scripts
- **Encryption Libraries**: Secure storage of sensitive data

## Installation

### Chrome Extension
1. Clone this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable **Developer mode**
4. Click **Load unpacked** and select the repository folder

### Backend (PostgreSQL)
1. Create a PostgreSQL database
2. Run migration scripts from `db/migrations`
3. Start the API server: `npm run start:api`

### Admin Dashboard
1. Install dependencies: `npm install`
2. Start the React app: `npm run dev`

## Usage

### Form Automation
1. Navigate to any web form
2. Click the extension icon
3. Select or create a profile
4. Map form fields (auto-mapping available)
5. Run automation

### Analytics
View form performance metrics in the React admin dashboard.

## Security
All form data is encrypted before storage using industry-standard algorithms.

## Contributing
Pull requests are welcome! Please open an issue first to discuss changes.
