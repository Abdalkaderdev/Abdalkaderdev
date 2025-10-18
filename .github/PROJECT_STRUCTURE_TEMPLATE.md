# Project Structure Template

This template provides a standardized structure for all repositories in the Abdalkader ecosystem.

```
your-project/
├── .github/                    # GitHub configuration
│   ├── workflows/              # CI/CD pipelines
│   │   ├── ci.yml             # Main CI workflow
│   │   ├── nextjs-ci.yml      # Next.js specific workflow
│   │   └── react-library-ci.yml # React library workflow
│   ├── ISSUE_TEMPLATE/        # Issue templates
│   │   ├── bug_report.md      # Bug report template
│   │   └── feature_request.md # Feature request template
│   ├── PULL_REQUEST_TEMPLATE.md # PR template
│   ├── CONTRIBUTING.md        # Contributing guidelines
│   └── assets/                # GitHub assets
│       └── social.png         # Social preview image
├── docs/                      # Project documentation
│   ├── api/                   # API documentation
│   ├── guides/                # User guides
│   └── examples/              # Code examples
├── src/                       # Source code
│   ├── components/            # Reusable components
│   │   ├── ui/               # Basic UI components
│   │   ├── forms/            # Form components
│   │   └── layout/           # Layout components
│   ├── lib/                  # Utilities and helpers
│   │   ├── utils.ts          # General utilities
│   │   ├── api.ts            # API functions
│   │   └── constants.ts      # Constants
│   ├── types/                # TypeScript definitions
│   │   ├── index.ts          # Main types export
│   │   └── api.ts            # API types
│   ├── hooks/                # Custom React hooks
│   │   ├── useApi.ts         # API hook
│   │   └── useLocalStorage.ts # Local storage hook
│   ├── styles/               # Styling
│   │   ├── globals.css       # Global styles
│   │   ├── components.css    # Component styles
│   │   └── variables.css     # CSS variables
│   ├── pages/                # Page components (Next.js)
│   │   ├── api/              # API routes
│   │   ├── _app.tsx          # App component
│   │   └── index.tsx         # Home page
│   └── app/                  # App directory (Next.js 13+)
│       ├── layout.tsx        # Root layout
│       ├── page.tsx          # Home page
│       └── globals.css       # Global styles
├── public/                   # Static assets
│   ├── images/              # Image assets
│   ├── icons/               # Icon assets
│   └── favicon.ico          # Favicon
├── tests/                   # Test files
│   ├── __mocks__/           # Mock files
│   ├── components/          # Component tests
│   ├── hooks/               # Hook tests
│   └── utils/               # Utility tests
├── .storybook/              # Storybook configuration
│   ├── main.js              # Main config
│   ├── preview.js           # Preview config
│   └── addons.js            # Addon configuration
├── .vscode/                 # VS Code configuration
│   ├── settings.json        # Workspace settings
│   ├── extensions.json      # Recommended extensions
│   └── launch.json          # Debug configuration
├── .eslintrc.js             # ESLint configuration
├── .prettierrc              # Prettier configuration
├── .gitignore               # Git ignore rules
├── .lighthouserc.json       # Lighthouse CI configuration
├── jest.config.js           # Jest configuration
├── next.config.js           # Next.js configuration
├── tailwind.config.js       # Tailwind CSS configuration
├── tsconfig.json            # TypeScript configuration
├── package.json             # Package configuration
├── README.md                # Project documentation
├── CONTRIBUTING.md          # Contributing guidelines
├── CHANGELOG.md             # Change log
└── LICENSE                  # License file
```

## File Naming Conventions

### Components
- Use PascalCase for component files: `Button.tsx`, `UserProfile.tsx`
- Use kebab-case for component directories: `user-profile/`, `data-table/`

### Utilities and Hooks
- Use camelCase for utility files: `formatDate.ts`, `useApi.ts`
- Use kebab-case for utility directories: `date-utils/`, `api-utils/`

### Pages and Routes
- Use kebab-case for page files: `user-profile.tsx`, `contact-us.tsx`
- Use camelCase for API routes: `getUser.ts`, `createPost.ts`

### Styles
- Use kebab-case for CSS files: `button-styles.css`, `layout-grid.css`
- Use camelCase for CSS modules: `Button.module.css`, `Layout.module.css`

## Directory Guidelines

### `/src/components/`
- Organize by feature or type
- Keep components small and focused
- Use index files for clean imports

### `/src/lib/`
- Pure utility functions
- No React-specific code
- Well-tested and documented

### `/src/hooks/`
- Custom React hooks
- Reusable stateful logic
- Follow React hooks rules

### `/src/types/`
- TypeScript type definitions
- API response types
- Component prop types

### `/docs/`
- User-facing documentation
- API documentation
- Code examples and guides

## Import Organization

```typescript
// 1. React and Next.js imports
import React from 'react'
import { NextPage } from 'next'

// 2. Third-party library imports
import { clsx } from 'clsx'
import { format } from 'date-fns'

// 3. Internal imports (absolute paths)
import { Button } from '@/components/ui/Button'
import { useApi } from '@/hooks/useApi'

// 4. Internal imports (relative paths)
import './Component.css'
import { localUtil } from './utils'
```

## Configuration Files

### Package.json
- Use semantic versioning
- Include all necessary scripts
- Specify exact dependency versions

### TypeScript
- Strict mode enabled
- Path mapping for clean imports
- Proper type checking

### ESLint
- React and TypeScript rules
- Import organization
- Code quality rules

### Prettier
- Consistent code formatting
- Trailing commas
- Single quotes

This structure ensures consistency across all projects and makes it easy for contributors to understand and navigate the codebase.