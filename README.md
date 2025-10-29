# Customizable Blog Builder

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![React](https://img.shields.io/badge/react-18.x-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Project Overview
Customizable Blog Builder is a powerful content management system with drag-and-drop editor, SEO optimization tools, and multi-theme support for creating beautiful, professional blogs without coding.

## Tech Stack
- **Frontend**: React.js, Next.js, Draft.js, TailwindCSS
- **Backend**: Node.js, Express.js, GraphQL
- **Database**: MongoDB, Redis
- **Editor**: Draft.js, Slate.js
- **SEO**: Next-SEO, React Helmet
- **Media**: Cloudinary, AWS S3
- **Testing**: Jest, Cypress, React Testing Library

## Features
- ✅ Drag-and-drop page builder
- ✅ Rich text editor
- ✅ Multiple pre-built themes
- ✅ Custom CSS/JS injection
- ✅ SEO optimization tools
- ✅ Meta tags management
- ✅ Responsive design preview
- ✅ Media library management
- ✅ Blog post scheduling
- ✅ Comment system
- ✅ User authentication
- ✅ Analytics integration

## Setup Instructions

### Prerequisites
- Node.js 16.x or higher
- MongoDB
- Redis (optional)

### Installation

```bash
# Clone the repository
git clone https://github.com/shithel9360/customizable-blog-builder.git
cd customizable-blog-builder

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configurations

# Run database setup
npm run db:init

# Start development server
npm run dev

# Build for production
npm run build
npm start
```

### Running Tests

```bash
# Run all tests
npm test

# Run unit tests
npm run test:unit

# Run E2E tests
npm run test:e2e

# Test coverage
npm run test:coverage
```

## Demo

![Demo GIF Placeholder](https://via.placeholder.com/800x400.png?text=Blog+Builder+Demo)

## API Documentation

View GraphQL API at `/graphql` when server is running.

## Contributing

Contributions welcome! See CONTRIBUTING.md for details.

## License

MIT License - see LICENSE file for details

## Contact

Shithel - [@shithel9360](https://github.com/shithel9360)
