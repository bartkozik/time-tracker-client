# Time Tracking & Reporting System (NDA Project)

**Note:** This is a portfolio overview of a commercial project developed under NDA. The source code is not publicly available.

## 📌 Project Overview

**Time Tracking** is a professional web-based system for tracking, managing, and reporting working hours. It was designed to help teams and managers monitor time allocation across projects, analyze productivity, and generate insightful reports for internal and external stakeholders.

This project was developed for a corporate client in a B2B setting.

## 👨‍💻 My Role

During the initial development phase, I worked as the **sole frontend developer** for approximately 6 months. I also contributed further reporting, accessibility and testing improvements in 2026. My responsibilities included:

- Designing the architecture of the frontend from scratch using **React 18 + TypeScript**
- Creating a dynamic UI for tracking and editing time entries
- Implementing **state management** with MobX
- Integrating the app with backend services via **Axios (REST API)**
- Managing translations and internationalization with **i18next**
- Setting up **form validation** using Zod
- Adding **animations and UI transitions** with Framer Motion
- Developing reusable UI components with attention to accessibility and performance
- Writing **unit and e2e tests** using Testing Library and Playwright
- Maintaining a consistent and clean codebase using **ESLint, Prettier, and Husky hooks**
- **Working without a complete design specification** – many UI/UX decisions were made independently based on direct user testing and feedback
  
- Throughout the development, I worked closely with backend developers and testers, ensuring smooth data synchronization and form behavior. Communication played a crucial role, especially during regular sprint reviews and backlog refinements held in Agile teams managed via Jira. Despite the lack of complete design specs, I frequently collaborated with stakeholders to clarify expectations and adjust the UI accordingly. I used Figma as a reference point and relied on solid time management to balance delivery and refinement cycles.

## 🆕 Recent Contributions in 2026

- **Reporting and billing interfaces:** Developed configurable pivot tables, report filters, worklog correction history and role-dependent workflows.
- **Accessible shared controls:** Improved keyboard interactions and ARIA semantics for select controls, tooltips, checkboxes and pivot field selection.
- **Internationalization:** Implemented Polish and English billing and reporting messages using i18next and ICU formatting.
- **Component regression tests:** Extended React Testing Library and Vitest coverage for shared controls, filters and reporting behavior.
- **End-to-end verification:** Expanded Playwright regression coverage, integrated verification into CI and added live staging smoke checks for critical user journeys.
- **Maintainable integration:** Worked on typed billing configuration requests, reusable controls and responsive history views.

These contributions extended the original time-entry application into a more capable reporting interface with explicit access rules, consistent components and automated regression checks.

## 🛠️ Tech Stack

### Frontend
- **React 18**
- **TypeScript**
- **MobX** (state management)
- **SCSS / SASS** (styling)
- **TanStack Query** (server-state integration)
- **Vite** (current build tooling)
- **Framer Motion** (animations)
- **Zod** (form validation)
- **React Router DOM** (routing)
- **i18next** (internationalization)

### Tooling & Dev Experience
- **ESLint + Prettier + Husky**
- **Playwright**, **React Testing Library**, **Vitest**
- **GitLab CI** (automated verification)
- **Yarn 4 (Berry)**
- **SVGO** (SVG optimization)
- **Prettier-plugin-sort-imports**

### Notable Libraries
- `@dnd-kit` – for implementing intuitive drag & drop UI
- `clsx`, `lodash`, `uuid`, `qs`

## 🧠 Key Challenges & Solutions

- **Customizable time-entry forms:** Implemented flexible UI components capable of handling varying input patterns and validation rules using Zod.
- **Optimized rendering:** Improved performance on complex table views with MobX observables and memoization.
- **Multi-language support:** Integrated `i18next` with ICU message formatting for dynamic content translation.
- **Clean code practices:** Enforced code consistency with auto-formatting and import sorting.

## 🚀 Outcome

- The frontend was successfully integrated into the client's ecosystem and rolled out internally.
- Developed responsive interfaces with keyboard and ARIA improvements across multiple roles (employees, managers, and HR staff).
- Expanded component and end-to-end regression coverage and maintained tooling and documentation for continued development.

---

_Interested in more technical details? I'd be happy to walk through the implementation during an interview or private discussion._
