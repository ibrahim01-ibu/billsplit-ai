# BillSplit AI

AI-powered bill splitting application monorepo.

## Project Structure

```
billsplit-ai/
├── backend/          # Node.js Express API server
├── mobile/           # React Native + Expo mobile app
├── docs/             # Project documentation
├── scripts/          # Deployment and automation scripts
└── package.json      # Root workspace configuration
```

## Getting Started

### Prerequisites

- Node.js >= 18.0.0
- npm >= 9.0.0

### Installation

Install all workspace dependencies:

```bash
npm install
```

### Development

Run backend:
```bash
npm run backend
```

Run mobile app:
```bash
npm run mobile
```

## Workspaces

This monorepo uses npm workspaces to manage multiple packages:

- `@billsplit-ai/backend` - Backend API
- `@billsplit-ai/mobile` - Mobile application

## Documentation

See the [docs](./docs) directory for detailed documentation.

## Scripts

- `npm run backend` - Start backend development server
- `npm run mobile` - Start mobile development server
- `npm run install-all` - Install all dependencies
- `npm run clean` - Clean all workspaces

## License

ISC
