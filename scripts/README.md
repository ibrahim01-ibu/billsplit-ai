# BillSplit AI - Scripts

This directory contains deployment and automation scripts for the BillSplit AI project.

## Contents

- **Deployment**: Scripts for deploying to various environments
- **Database**: Database migration and seed scripts
- **Build**: Build automation scripts
- **Testing**: Test automation and CI/CD scripts
- **Utilities**: Helper scripts for development tasks

## Usage

Scripts should be executable and include proper documentation at the top of each file.

### Example Structure

```
scripts/
├── deploy/
│   ├── deploy-backend.sh
│   └── deploy-mobile.sh
├── db/
│   ├── migrate.js
│   └── seed.js
├── build/
│   └── build-all.sh
└── utils/
    └── cleanup.sh
```

## Best Practices

1. Make scripts idempotent when possible
2. Include error handling and logging
3. Document required environment variables
4. Test scripts in staging before production
5. Use version control for all scripts
