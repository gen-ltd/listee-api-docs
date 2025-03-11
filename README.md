# Listee API Documentation

This repository contains the OpenAPI specification and documentation for the Listee Task Management API.

## Overview

Listee API allows developers to programmatically access and manage task data within the Listee task management platform. The API documentation is built using OpenAPI 3.1.0 specification and rendered with Redoc.

## Live Documentation

The latest version of the API documentation is published at:
[https://gen-ltd.github.io/listee-api-docs/](https://gen-ltd.github.io/listee-api-docs/)

## API Features

- **Authentication** via API key
- **Categories Management**: Create, read, update and delete task categories
- **Tasks Management**: Create, update, organize and delete tasks within categories
- **Bulk Operations**: Reordering tasks, bulk deletion, moving tasks between categories

## Development

### Prerequisites

- Node.js (v18 or later)
- npm

### Setup

```bash
# Clone the repository
git clone https://github.com/gen-ltd/listee-api-docs.git
cd listee-api-docs

# Install dependencies
npm install
```

### Available Scripts

- `npm run dev` - Preview documentation locally at http://localhost:8080
- `npm run build` - Build static HTML documentation to the `public` directory
- `npm run lint` - Lint the OpenAPI specification for errors and best practices

### File Structure

- `openapi.yaml` - OpenAPI specification for the Listee API
- `package.json` - Project configuration and dependencies
- `.github/workflows/gh-pages.yaml` - GitHub Actions workflow for deployment

## Deployment

The documentation is automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch. The deployment uses GitHub Actions as defined in `.github/workflows/gh-pages.yaml`.

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions regarding the API or documentation, contact:
- Email: listee@gen-ltd.jp
```
