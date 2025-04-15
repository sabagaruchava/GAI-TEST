## Features

- User authentication and role-based authorization
- Vehicle browsing and search
- Shipping calculator
- Admin panel for managing users and vehicles
- Multi-language support (English, Georgian, Russian)
- Image handling and ZIP download
- Contact form

## Tech Stack

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Drizzle ORM
- SQLite database
- Lucia for authentication
- AWS S3 for image storage
- React Email for email sending
- Zod for schema validation

## Getting Started

### Prerequisites

- Node.js 16.0.0 or later
- npm or yarn

## Project Structure

- `src/app`: Next.js app router and page components
- `src/components`: Reusable React components
- `src/lib`: Utility functions, database setup, and server actions
- `src/messages`: Internationalization JSON files
- `public`: Static assets

## Key Components

- `AuthActions`: Handles user authentication (login, register, logout)
- `DownloadButton`: Allows users to download vehicle images as a ZIP file
- `ShippingCalculator`: Calculates shipping costs for vehicles
- `LocaleSwitcher`: Enables language switching

## Deployment

This project is set up for deployment on Vercel. Connect your GitHub repository to Vercel for automatic deployments.

## Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request
