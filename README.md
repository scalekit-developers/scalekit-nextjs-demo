<p align="left">
  <a href="https://scalekit.com" target="_blank" rel="noopener noreferrer">
    <picture>
      <img src="https://cdn.scalekit.cloud/v1/scalekit-logo-dark.svg" height="64">
    </picture>
  </a>
  <br/>
</p>

# Scalekit Next.js Demo App

[![Next.js](https://img.shields.io/badge/Next.js-13+-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)

A modern Next.js application demonstrating <a href="https://scalekit.com" target="_blank" rel="noopener noreferrer">Scalekit</a>'s enterprise authentication capabilities. This example showcases how to implement SSO authentication flows in a React/Next.js application using the app router.

Scalekit provides auth and actions on behalf of users, with 500+ connectors and 20,000+ tools.

## 🚀 What This Demo Shows

- **Enterprise SSO Integration**: SAML/OIDC authentication flows using Scalekit
- **Next.js App Router**: Modern Next.js 13+ patterns with server actions
- **Session Management**: Secure authentication state with HTTP-only cookies
- **OAuth 2.0 Flows**: Authorization code flow with CSRF protection
- **User Profile Management**: Authenticated user data display
- **Modern UI/UX**: Clean, responsive interface with Tailwind CSS

## 🚀 Quick Start

### Prerequisites

1. [Sign up](https://scalekit.com) for a Scalekit account
2. Get your `env_url`, `client_id` and `client_secret` from the Scalekit dashboard

### Installation

```bash
# Clone the repository
git clone https://github.com/scalekit-developers/scalekit-nextjs-demo.git
cd scalekit-nextjs-demo

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### Configuration

1. Copy the environment variables:
```bash
cp .env.example .env.local
```

2. Update `.env.local` with your Scalekit credentials:
```bash
SCALEKIT_ENV_URL=your_env_url
SCALEKIT_CLIENT_ID=your_client_id  
SCALEKIT_CLIENT_SECRET=your_client_secret
```

### Development

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🔧 Tech Stack

- **Framework**: Next.js 13+ with App Router
- **Language**: TypeScript
- **Authentication**: Scalekit SDK
- **Styling**: Tailwind CSS (if configured)
- **Font**: Inter (optimized with `next/font`)

## 🔗 Helpful Links

### 📖 Quickstart Guides
- [**SSO Integration**](https://docs.scalekit.com/sso/quickstart/) - Implement enterprise Single Sign-on
- [**Full Stack Auth**](https://docs.scalekit.com/fsa/quickstart/) - Complete authentication solution
- [**Passwordless Auth**](https://docs.scalekit.com/passwordless/quickstart/) - Modern authentication flows
- [**Social Logins**](https://docs.scalekit.com/social-logins/quickstart/) - Popular social identity providers
- [**Machine-to-Machine**](https://docs.scalekit.com/m2m/quickstart/) - API authentication

### 📚 Documentation & Reference
- [**API Reference**](https://docs.scalekit.com/apis) - Complete API documentation
- [**Developer Kit**](https://docs.scalekit.com/dev-kit/) - Tools and utilities
- [**API Authentication Guide**](https://docs.scalekit.com/guides/authenticate-scalekit-api/) - Secure API access

### 🛠️ Additional Resources
- [**Setup Guide**](https://docs.scalekit.com/guides/setup-scalekit/) - Initial platform configuration
- [**Code Examples**](https://docs.scalekit.com/directory/code-examples/) - Ready-to-use code snippets
- [**Admin Portal Guide**](https://docs.scalekit.com/directory/guides/admin-portal/) - Administrative interface

## 📱 More Example Apps

Explore other Scalekit integrations:

| Framework | Repository | Description |
|-----------|------------|-------------|
| **Express.js** | [scalekit-express-example](https://github.com/scalekit-developers/scalekit-express-example) | Node.js/Express integration |
| **FastAPI** | [scalekit-fastapi-example](https://github.com/scalekit-developers/scalekit-fastapi-example) | Python/FastAPI integration |
| **Go** | [scalekit-go-example](https://github.com/scalekit-developers/scalekit-go-example) | Go HTTP server integration |
| **Spring Boot** | [scalekit-springboot-example](https://github.com/scalekit-developers/scalekit-springboot-example) | Java/Spring Boot integration |

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
