# GitHub Topics Configuration

This document outlines the standardized topics and metadata for all repositories in the Abdalkader ecosystem.

## Core Topics

### Technology Stack
- `react` - React.js framework
- `typescript` - TypeScript language
- `nextjs` - Next.js framework
- `tailwindcss` - Tailwind CSS framework
- `nodejs` - Node.js runtime
- `javascript` - JavaScript language

### Project Types
- `portfolio` - Portfolio projects
- `component-library` - Reusable component libraries
- `blog` - Blog or content management
- `api` - API or backend services
- `frontend` - Frontend applications
- `fullstack` - Full-stack applications

### Features
- `responsive` - Responsive design
- `pwa` - Progressive Web App
- `ssr` - Server-side rendering
- `ssg` - Static site generation
- `cms` - Content management
- `ecommerce` - E-commerce functionality

### Deployment
- `vercel` - Deployed on Vercel
- `netlify` - Deployed on Netlify
- `aws` - Deployed on AWS
- `docker` - Dockerized application

### Development
- `monorepo` - Monorepo structure
- `storybook` - Storybook documentation
- `testing` - Comprehensive testing
- `ci-cd` - Continuous integration/deployment

### Brand
- `abdalkader-dev` - Abdalkader brand
- `open-source` - Open source project
- `template` - Project template
- `boilerplate` - Code boilerplate

## Repository-Specific Topics

### Portfolio Projects
```
react, typescript, nextjs, tailwindcss, portfolio, responsive, vercel, abdalkader-dev
```

### Component Libraries
```
react, typescript, component-library, storybook, npm, open-source, abdalkader-dev
```

### Blog Projects
```
react, typescript, nextjs, blog, cms, ssg, vercel, abdalkader-dev
```

### API Projects
```
nodejs, typescript, api, express, mongodb, aws, abdalkader-dev
```

### Full-Stack Projects
```
react, typescript, nextjs, nodejs, fullstack, mongodb, vercel, abdalkader-dev
```

## Repository Descriptions

### Standard Format
```
[Project Type]: [Brief Description] | Built with [Tech Stack] | [Live Demo Link]
```

### Examples
```
Portfolio: Modern portfolio website showcasing projects and skills | Built with React, TypeScript, Next.js | abdalkader.dev

Component Library: Reusable React components with Storybook documentation | Built with React, TypeScript, Tailwind CSS | storybook.abdalkader.dev

Blog: Technical blog with MDX support and dark mode | Built with Next.js, TypeScript, Tailwind CSS | blog.abdalkader.dev
```

## README Badges

### Standard Badges
```markdown
![Live Demo](https://img.shields.io/badge/Live%20Demo-000000?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)
```

### Technology Badges
```markdown
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
```

### Status Badges
```markdown
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg?style=for-the-badge)
![Coverage](https://img.shields.io/badge/coverage-90%25-brightgreen.svg?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=for-the-badge)
```

## Social Preview Images

### Dimensions
- **Width**: 1200px
- **Height**: 630px
- **Format**: PNG or JPG
- **File size**: < 1MB

### Design Guidelines
- Include project name
- Use Abdalkader brand colors
- Include relevant technology logos
- Keep text readable at small sizes
- Use consistent branding

### File Naming
- `social.png` - Main social preview
- `social-dark.png` - Dark mode version
- `social-light.png` - Light mode version

## Repository Settings

### General Settings
- **Description**: Use standard format
- **Website**: Link to live demo
- **Topics**: Add all relevant topics
- **Social preview**: Upload custom image

### Features
- **Issues**: Enabled with templates
- **Projects**: Enabled for project management
- **Wiki**: Disabled (use docs folder)
- **Discussions**: Enabled for community

### Security
- **Dependency alerts**: Enabled
- **Security advisories**: Enabled
- **Code scanning**: Enabled
- **Secret scanning**: Enabled

## Automation Scripts

### Add Topics Script
```bash
#!/bin/bash
# Add topics to repository
gh repo edit Abdalkaderdev/your-repo --add-topic "react,typescript,nextjs,tailwindcss,portfolio,responsive,vercel,abdalkader-dev"
```

### Update Description Script
```bash
#!/bin/bash
# Update repository description
gh repo edit Abdalkaderdev/your-repo --description "Portfolio: Modern portfolio website showcasing projects and skills | Built with React, TypeScript, Next.js | abdalkader.dev"
```

## Monitoring and Analytics

### GitHub Insights
- Track repository views
- Monitor clone statistics
- Analyze traffic sources
- Review popular content

### External Analytics
- Google Analytics for live demos
- Vercel Analytics for performance
- Hotjar for user behavior
- Sentry for error tracking

This configuration ensures consistent branding and discoverability across all repositories in the Abdalkader ecosystem.