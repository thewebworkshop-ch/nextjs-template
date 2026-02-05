# Next.js Template

Production-ready Next.js template

## Tech Stack

| Category           | Technology                   |
| ------------------ | ---------------------------- |
| **Framework**      | Next.js, React, TypeScript   |
| **Styling**        | Tailwind CSS, shadcn/ui, CVA |
| **Database**       | Prisma ORM + PostgreSQL      |
| **Authentication** | NextAuth.js                  |
| **Forms**          | React Hook Form + Zod        |
| **Emails**         | Resend                       |
| **Environment**    | t3-oss/env (type-safe)       |

## Quality & Testing

| Category           | Technology                             |
| ------------------ | -------------------------------------- |
| **Unit Tests**     | Vitest + React Testing Library         |
| **E2E Tests**      | Playwright (Chromium, Firefox, WebKit) |
| **API Mocking**    | MSW (Mock Service Worker)              |
| **Component Docs** | Storybook                              |
| **Formatting**     | Prettier                               |
| **Linting**        | ESLint                                 |
| **Git Hooks**      | Husky                                  |

## Git Hooks

| Hook           | Technology                                |
| -------------- | ----------------------------------------- |
| **Pre-commit** | Gitleaks + lint-staged + TypeScript check |
| **Commit-msg** | commitlint                                |
| **Pre-push**   | Unit tests + build verification           |

## Security & CI/CD

| Category                   | Technology                        |
| -------------------------- | --------------------------------- |
| **CI/CD**                  | GitHub Actions                    |
| **Secret Scanning**        | Gitleaks + GitHub Secret Scanning |
| **Vulnerability Scanning** | Snyk + Dependabot Alerts          |
| **Dependency Updates**     | Renovate                          |
| **Code Coverage**          | Codecov                           |
| **Code Quality**           | DeepSource                        |
| **Security Headers**       | CSP, HSTS, X-Frame-Options        |

## Environment Variables

Environment variables are managed through Infisical and validated at runtime using `@t3-oss/env-nextjs`.

## Docker

Optimized production image using multi-stage build with Node.js on Debian slim for minimal size and enhanced security.

<br>

© [The Web Workshop](https://thewebworkshop.ch)
