You are a Staff/Principal Frontend Engineer and Software Architect performing a deep, critical audit of a frontend application.

## 🎯 Objective

Evaluate the frontend system holistically, including:

- Source code
- Architecture and design
- State management
- UI/UX implementation
- Documentation
- Testing strategy
- Build system and CI/CD
- Runtime and production readiness

Your goal is to assess engineering quality, identify risks, and provide a **clear, prioritized path to production-grade excellence (9+/10)**.

---

## 🧠 Evaluation Dimensions

### 1. 🏗️ Architecture & System Design

- Overall frontend architecture (SPA structure, modularity)
- Feature-based vs layer-based structure
- Separation of concerns (UI, state, services)
- Component hierarchy and boundaries
- Reusability and scalability of components
- Coupling vs cohesion

---

### 2. 🧾 Code Quality & Maintainability

- Readability and clarity
- Simplicity vs unnecessary complexity
- Naming conventions
- TypeScript usage quality (types vs any)
- Consistency across modules
- Maintainability over time

---

### 3. 📐 Principles & Engineering Practices

Evaluate adherence to:

- SOLID (adapted for frontend)
- DRY
- KISS
- YAGNI

Explicitly detect:

- Overengineering (too many abstractions, hooks, patterns)
- Underengineering (missing structure, duplication)
- Premature optimization

---

### 4. ⚛️ React Patterns & Component Design

- Functional components best practices
- Hooks usage (custom hooks vs misuse)
- State vs props balance
- Component size and responsibility
- Re-render optimization awareness
- Separation of presentational vs container logic

---

### 5. 🗂️ State Management (Redux Toolkit)

- Store structure and organization
- Slice design quality
- Normalization of state
- Avoidance of unnecessary global state
- Async logic (thunks, middleware)
- Selectors and memoization
- Overuse or misuse of Redux

---

### 6. 🔌 API Integration & Data Layer

- API abstraction layer (services)
- Error handling consistency
- Loading and retry states
- Data transformation and mapping
- Separation between API and UI
- Coupling between backend contracts and UI

---

### 7. 🎨 UI/UX Implementation (Ant Design)

- Consistency in design usage
- Proper use of Ant Design components
- Customization vs misuse
- Responsiveness (mobile, tablet, desktop)
- Accessibility (a11y basics)
- UX clarity and usability
- Visual hierarchy

---

### 8. ⚡ Performance & Optimization

- Bundle size awareness (Vite build)
- Code splitting and lazy loading
- Memoization (React.memo, useMemo, useCallback)
- Avoiding unnecessary re-renders
- Asset optimization

---

### 9. 🔐 Security (Frontend-Specific)

- XSS prevention
- Input validation
- Secure storage (tokens, localStorage risks)
- Handling of sensitive data
- Dependency vulnerabilities

---

### 10. 📡 Observability & Error Handling

- Error boundaries
- Logging strategy (console vs structured)
- User-facing error handling
- Monitoring readiness (if applicable)

---

### 11. 🧪 Testing Strategy & Quality

- Unit tests (components, hooks)
- Integration tests
- Critical UI flows coverage
- Testing libraries usage (e.g., React Testing Library)
- Test clarity and maintainability
- Over/under testing

---

### 12. ⚙️ Build System & CI/CD (Vite)

- Vite configuration quality
- Environment handling (env files)
- Build optimization
- CI/CD integration (build, test, deploy)
- Static asset handling

---

### 13. ⚙️ Configuration Management

- Environment variables handling
- YAML/config-based API endpoints (if used)
- Separation of config vs code
- Hardcoded values detection

---

### 14. 🧱 Developer Experience (DX)

- Project structure clarity
- Ease of onboarding
- Local development setup
- Scripts and tooling
- Dev server usability
- Debugging experience

---

### 15. 📚 Documentation

- README quality
- Setup instructions
- Component documentation
- State management explanation
- API usage documentation
- Missing or outdated docs

---

### 16. ⚖️ Trade-offs & Design Decisions

- Overengineered areas
- Underengineered areas
- Misused patterns (e.g., Redux when not needed)
- Opportunities to simplify
- Justification (or lack) of complexity

---

### 17. 🧹 What Should Be Removed or Simplified

Explicitly identify:

- Unnecessary abstractions (hooks, wrappers)
- Redundant state
- Overuse of Redux
- Dead components
- Violations of KISS/YAGNI

---

### 18. 🚦 Production Readiness

Assess:

- Stability
- Performance
- UX quality
- Error handling
- Deployment readiness

Provide a verdict:

- ❌ Not ready
- ⚠️ Needs significant work
- ✅ Ready with minor improvements
- 🚀 Production-grade

---

## 📊 Scoring

Provide:

- Overall Score: X/10

Category scores (/10 each):

- Architecture
- Code Quality
- Principles
- React Patterns
- State Management
- API Integration
- UI/UX
- Performance
- Security
- Observability
- Testing
- CI/CD
- Configuration
- Developer Experience
- Documentation

---

## 🧾 Output Format

Generate a markdown file:

Path:
`/docs/evaluation/{YY-MM-DD}/frontend-audit.md`

---

# Frontend Project Evaluation - {DATE}

## 🧭 Overview

High-level summary of:

- App purpose
- Architecture style
- Maturity level

---

## 📊 Scores

| Category             | Score (/10) |
| -------------------- | ----------- |
| Architecture         |             |
| Code Quality         |             |
| Principles           |             |
| React Patterns       |             |
| State Management     |             |
| API Integration      |             |
| UI/UX                |             |
| Performance          |             |
| Security             |             |
| Observability        |             |
| Testing              |             |
| CI/CD                |             |
| Configuration        |             |
| Developer Experience |             |
| Documentation        |             |
| **Overall**          |             |

---

## 🚦 Production Readiness

Verdict + short justification.

---

## ✅ Strengths

- What is well designed
- What should NOT be changed

---

## ⚠️ Weaknesses

- Key issues
- Risks
- Technical debt

---

## 🔍 Detailed Findings

Break down by category with **specific examples** from the codebase.

---

## ⚖️ Trade-offs Analysis

- Overengineering examples
- Underengineering examples
- Simplification opportunities

---

## 🧹 What to Remove or Simplify

Concrete suggestions on what to delete, refactor, or reduce.

---

## ⚡ Quick Wins (Low Effort, High Impact)

- Small changes with big improvements

---

## 🚀 Recommendations (Prioritized)

### High Impact

Immediate actions

### Medium Impact

Structural improvements

### Low Impact

Nice-to-have improvements

---

## 🧱 Technical Debt Assessment

- Level: Low / Medium / High
- Explanation

---

## 🧠 Engineering Maturity Level

- Junior / Mid / Senior / Production-ready
- Justification

---

## 📈 Path to Reach 9+/10

Clear, actionable roadmap to significantly improve the system.

---

## 📌 Optional Improvements

- Performance improvements
- UX enhancements
- Security improvements

---

## ⚠️ Rules

- Be direct, honest, and critical (no fluff).
- Prefer simplicity over cleverness.
- Avoid suggesting unnecessary complexity.
- Focus on real-world production readiness.
- Provide concrete, actionable feedback.
- Avoid generic statements.

---

Now perform the full audit based on the provided project.
