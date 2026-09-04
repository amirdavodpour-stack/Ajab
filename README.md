# HOPE Marketplace — Multi-Vertical Super-App Platform

**Wave 2 | Session 13 → Ongoing Transformation**

HOPE is a professional multi-vertical marketplace and super-app platform, evolving from an initial jobs vertical into a cohesive, production-grade ecosystem supporting jobs, services, products, bookings, and more.

## 📋 Quick Links

- **Master Plan**: [docs/roadmap/SUPERPROMPT.md](docs/roadmap/SUPERPROMPT.md)
- **Roadmap**: [docs/roadmap/MULTI-VERTICAL-ROADMAP.md](docs/roadmap/MULTI-VERTICAL-ROADMAP.md)
- **Architecture**: [docs/architecture/](docs/architecture/)
- **Database Schema**: [docs/database/](docs/database/)
- **API & Backend**: [backend/](backend/)
- **Mobile (Flutter)**: [mobile/](mobile/)

## 🚀 Getting Started

### Prerequisites
- **Flutter** 3.13+ (Dart 3.1+)
- **Node.js** 18+ / npm or yarn
- **PostgreSQL** 14+
- **Android SDK** (for mobile builds)

### Backend Setup
```bash
cd backend
npm install
npm run dev
# Backend runs on http://localhost:3000
```

### Flutter Mobile Setup
```bash
cd mobile
flutter pub get
flutter run
# Targets connected device or emulator
```

## 📁 Project Structure

```
ajab/
├── backend/                  # Node/Express API, domain logic, database
├── mobile/                   # Flutter application (iOS/Android)
├── docs/
│   ├── roadmap/             # 30-session master plan, roadmap
│   ├── architecture/        # ADRs, architecture decisions
│   ├── database/            # Schema, migrations, ER diagrams
│   ├── api/                 # API documentation, contracts
│   ├── design/              # Design system, components
│   ├── product/             # Product requirements, flows
│   ├── security/            # Security reviews, threat models
│   └── release/             # Release procedures, checklists
├── .github/workflows/        # CI/CD pipelines
└── README.md
```

## 📊 Current Status

| Metric | Status |
|--------|--------|
| **Wave** | 2 |
| **Current Session** | 13+ (ongoing) |
| **Jobs Vertical** | ✅ Functional |
| **Design System** | ✅ Implemented |
| **Multi-Vertical Framework** | ✅ In Place |
| **Search & Discovery** | ✅ Functional |
| **Messaging System** | ✅ Functional |
| **Notifications** | ✅ Event-driven |
| **Payments** | ⚙️ Provider-abstracted |

## 🎯 Primary Goals

1. **Protect existing jobs vertical** — zero regression
2. **Multi-vertical reusability** — shared architecture
3. **Production quality** — matching leading super-apps
4. **Security-first** — authorization, validation, abuse prevention
5. **Performance** — perceived and actual responsiveness
6. **Professional UX** — polished interactions, accessibility

## 📖 Documentation

- See **[docs/roadmap/SUPERPROMPT.md](docs/roadmap/SUPERPROMPT.md)** for the complete 30-session transformation plan
- See **[docs/roadmap/MULTI-VERTICAL-ROADMAP.md](docs/roadmap/MULTI-VERTICAL-ROADMAP.md)** for detailed feature roadmap
- See **[docs/architecture/](docs/architecture/)** for architectural decisions and design documents

## 🔧 Development Workflow

### Adding a Feature
1. Check the current session's goals in SUPERPROMPT.md
2. Read the relevant architecture ADRs
3. Implement following the design system
4. Test (unit, widget, integration where appropriate)
5. Update STATE at session end

### Running Tests
```bash
# Backend tests
cd backend
npm test

# Flutter widget/unit tests
cd mobile
flutter test
```

### Code Quality
```bash
# Flutter analysis
cd mobile
flutter analyze

# Backend linting
cd backend
npm run lint
```

## 📝 Session Tracking

Each session is self-contained and produces one primary deliverable. Sessions are tracked in:
- **[docs/roadmap/SUPERPROMPT.md](docs/roadmap/SUPERPROMPT.md)** — Master plan + STATE block
- State includes: progress log, decisions, open risks, next session details

---

**Last Updated**: Session 13+  
**Repository**: [github.com/amirdavodpour-stack/Ajab](https://github.com/amirdavodpour-stack/Ajab)  
**License**: See LICENSE file
