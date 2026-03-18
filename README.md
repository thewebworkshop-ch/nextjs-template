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
| **Env Variables**  | Infisical + t3-oss/env       |
| **Docker**         | Debian slim base image       |

## Quality & Testing

| Category            | Technology                                              |
| ------------------- | ------------------------------------------------------- |
| **Unit Tests**      | Vitest (80% per-file threshold) + React Testing Library |
| **E2E Tests**       | Playwright + axe-core                                   |
| **API Mocking**     | MSW (Mock Service Worker)                               |
| **Component Tests** | Storybook + Playwright + Vitest                         |
| **Formatting**      | Prettier                                                |
| **Linting**         | ESLint                                                  |
| **Type Check**      | TypeScript Compiler                                     |
| **Git Hooks**       | Husky                                                   |

## Security

| Category               | Technology                          |
| ---------------------- | ----------------------------------- |
| **Secret Scanning**    | GitHub Secret Protection + Gitleaks |
| **SCA**                | Trivy + Semgrep                     |
| **SAST**               | Semgrep                             |
| **License Compliance** | Trivy                               |
| **CIS Docker**         | Trivy                               |
| **IaC Scanning**       | Trivy                               |

## Dependency Management

| Category               | Technology |
| ---------------------- | ---------- |
| **Dependency Updates** | Renovate   |
| **Merge Queue**        | Aviator    |

## Git Hooks

| Category       | Technology                                                       |
| -------------- | ---------------------------------------------------------------- |
| **Pre-commit** | Gitleaks + lint-staged (Prettier & ESLint) + TypeScript Compiler |
| **Commit-msg** | commitlint                                                       |
| **Pre-push**   | Unit tests + Build verification                                  |

<br>

© [The Web Workshop](https://thewebworkshop.ch)
