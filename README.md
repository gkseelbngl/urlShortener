# 🔗 Modern URL Shortener

[Proje Canlı Demo Linki](https://urlshortenervia.netlify.app/)

Trimrr is a full-stack URL shortening service built with React, Node.js, and PostgreSQL. It allows users to create shortened URLs, track clicks, and manage their links through an intuitive dashboard.

## ✨ Features

### Core Functionality

- **URL Shortening**: Convert long URLs into short, memorable links
- **Custom Aliases**: Create custom short URLs (e.g., trimrr.in/mylink)
- **QR Code Generation**: Automatically generate QR codes for each shortened URL
- **Click Analytics**: Track total clicks, referrers, and geographic data
- **User Accounts**: Secure authentication with email/password or OAuth

### Dashboard Features

- **Link Management**: View, edit, and organize all your shortened URLs
- **Real-time Stats**: Visualize click data with interactive charts
- **Bulk Actions**: Delete or archive multiple links at once
- **Search & Filter**: Quickly find specific links in your collection

### Technical Highlights

- **Instant Redirects**: Near-zero latency when accessing shortened URLs
- **API Access**: RESTful endpoints for programmatic link management
- **Responsive Design**: Works perfectly on all device sizes
- **Dark/Light Mode**: Automatic theme switching based on system preferences

## 🛠️ Tech Stack

### Frontend

- **React** (Vite) - Frontend framework
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/ui** - Beautifully designed components
- **React Router** - Client-side routing
- **React Query** - Data fetching and caching
- **Zod** - Schema validation

### Backend

- **Node.js** - Runtime environment
- **Express** - Web application framework
- **PostgreSQL** - Relational database
- **Prisma** - ORM for database access
- **Redis** - Caching for high-performance redirects

### Authentication

- **JWT** - Secure token-based authentication
- **OAuth 2.0** - Social login integrations

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+)
- PostgreSQL (v15+)
- Redis (v7+)
- PNPM (recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gkseelbngl/urlShortener.git
   cd urlShortener
   ```
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```
   Fill in your configuration values in the _.env_ file
4. Run database migrations:
   ```bash
   pnpm prisma migrate dev
   ```
5. Start the development server:
   ```bash
   pnpm dev
   ```

### Deployment

The project includes Dockerfiles and can be deployed using:

```bash
docker-compose up --build
```

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Inspired by services like Bitly and TinyURL

- Built with amazing open source technologies

- Special thanks to all contributors
