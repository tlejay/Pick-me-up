# PICK-ME-UP Project Structure

## Directory Tree

```
Pick-me-up/
├── .gitignore                     # Git ignore configuration
├── README.md                      # Project overview
├── CLAUDE.md                      # AI development context and guidelines
├── Business_Context.md            # DOS company information
├── PROJECT_STRUCTURE.md           # This file
│
├── docs/                          # 📚 Documentation
│   ├── README.md                  # Documentation overview
│   ├── api/                       # API documentation
│   │   └── (API specs, Postman collections, OpenAPI)
│   ├── architecture/              # System architecture
│   │   ├── SYSTEM_OVERVIEW.md     # System architecture overview
│   │   └── (diagrams, technical designs)
│   ├── business/                  # Business requirements
│   │   └── (requirements, user stories, PRDs)
│   └── user-guides/               # User documentation
│       └── (manuals, tutorials, FAQs)
│
├── backend/                       # 🔧 Backend Services
│   ├── README.md                  # Backend setup guide
│   ├── package.json               # Node.js dependencies
│   ├── tsconfig.json              # TypeScript configuration
│   ├── src/                       # Source code
│   │   ├── agents/               # 🤖 AI Agents
│   │   │   ├── order-processing.agent.ts
│   │   │   ├── inventory.agent.ts
│   │   │   ├── notification.agent.ts
│   │   │   ├── queue-optimization.agent.ts
│   │   │   ├── recommendation.agent.ts
│   │   │   └── analytics.agent.ts
│   │   ├── api/                  # API endpoints
│   │   │   ├── routes/
│   │   │   ├── controllers/
│   │   │   └── middlewares/
│   │   ├── config/               # Configuration files
│   │   │   ├── database.config.ts
│   │   │   ├── firebase.config.ts
│   │   │   └── app.config.ts
│   │   ├── models/               # Data models
│   │   │   ├── user.model.ts
│   │   │   ├── order.model.ts
│   │   │   ├── store.model.ts
│   │   │   └── product.model.ts
│   │   ├── services/             # Business logic
│   │   │   ├── auth.service.ts
│   │   │   ├── order.service.ts
│   │   │   ├── payment.service.ts
│   │   │   └── notification.service.ts
│   │   └── utils/                # Utilities
│   │       ├── logger.ts
│   │       ├── validator.ts
│   │       └── helpers.ts
│   └── tests/                    # Tests
│       ├── unit/
│       ├── integration/
│       └── e2e/
│
├── mobile/                        # 📱 Mobile Application
│   ├── README.md                  # Mobile setup guide
│   ├── pubspec.yaml               # Flutter dependencies
│   ├── android/                   # Android configuration
│   ├── ios/                       # iOS configuration
│   ├── lib/                       # Flutter source code
│   │   ├── main.dart             # App entry point
│   │   ├── features/             # Feature modules
│   │   │   ├── auth/
│   │   │   ├── menu/
│   │   │   ├── orders/
│   │   │   ├── profile/
│   │   │   ├── payment/
│   │   │   └── rewards/
│   │   ├── shared/               # Shared components
│   │   │   ├── widgets/
│   │   │   ├── models/
│   │   │   └── constants/
│   │   └── core/                 # Core utilities
│   │       ├── services/
│   │       ├── utils/
│   │       └── config/
│   └── test/                     # Mobile tests
│       ├── widget_test/
│       └── unit_test/
│
├── web/                          # 🌐 Web Application
│   ├── README.md                 # Web setup guide
│   ├── package.json              # NPM dependencies
│   ├── tsconfig.json             # TypeScript configuration
│   ├── src/                      # Source code
│   │   ├── main.tsx              # App entry point
│   │   ├── components/           # React/Vue components
│   │   │   ├── common/
│   │   │   ├── layout/
│   │   │   └── forms/
│   │   ├── pages/                # Page components
│   │   │   ├── Dashboard.tsx
│   │   │   ├── Orders.tsx
│   │   │   ├── Menu.tsx
│   │   │   ├── Inventory.tsx
│   │   │   └── Analytics.tsx
│   │   ├── services/             # API services
│   │   │   ├── api.service.ts
│   │   │   └── auth.service.ts
│   │   ├── store/                # State management
│   │   │   ├── store.ts
│   │   │   └── slices/
│   │   └── utils/                # Utilities
│   │       └── helpers.ts
│   └── public/                   # Static assets
│       ├── index.html
│       ├── favicon.ico
│       └── assets/
│
├── infrastructure/               # ⚙️ DevOps & Infrastructure
│   ├── README.md                 # Infrastructure guide
│   ├── docker/                   # Docker configurations
│   │   ├── Dockerfile.backend
│   │   ├── Dockerfile.web
│   │   └── docker-compose.yml
│   ├── kubernetes/               # Kubernetes manifests
│   │   ├── deployments/
│   │   ├── services/
│   │   └── ingress/
│   └── terraform/                # Infrastructure as Code
│       ├── main.tf
│       ├── variables.tf
│       └── modules/
│
├── shared/                       # 🔄 Shared Code
│   ├── types/                    # TypeScript types
│   │   ├── user.types.ts
│   │   ├── order.types.ts
│   │   └── common.types.ts
│   └── constants/                # Shared constants
│       ├── api.constants.ts
│       └── app.constants.ts
│
└── scripts/                      # 🛠️ Utility Scripts
    ├── setup.sh                  # Project setup script
    ├── deploy.sh                 # Deployment script
    └── seed-data.ts              # Database seeding
```

## Key Files to Create Next

### Backend
- [ ] `backend/package.json` - Node.js dependencies
- [ ] `backend/tsconfig.json` - TypeScript configuration
- [ ] `backend/.env.example` - Environment variables template
- [ ] `backend/src/index.ts` - Main application entry point
- [ ] `backend/src/agents/base.agent.ts` - Base agent class

### Mobile
- [ ] `mobile/pubspec.yaml` - Flutter dependencies
- [ ] `mobile/lib/main.dart` - Application entry point
- [ ] `mobile/lib/core/config/app_config.dart` - App configuration
- [ ] `mobile/.env.example` - Environment variables template

### Web
- [ ] `web/package.json` - NPM dependencies
- [ ] `web/tsconfig.json` - TypeScript configuration
- [ ] `web/.env.example` - Environment variables template
- [ ] `web/src/main.tsx` - Application entry point
- [ ] `web/vite.config.ts` or `web/webpack.config.js` - Build configuration

### Infrastructure
- [ ] `infrastructure/docker/docker-compose.yml` - Local development setup
- [ ] `infrastructure/docker/Dockerfile.backend` - Backend container
- [ ] `infrastructure/terraform/main.tf` - Cloud infrastructure

### Documentation
- [ ] `docs/api/openapi.yaml` - API specification
- [ ] `docs/architecture/data-flow.md` - Data flow diagrams
- [ ] `docs/business/requirements.md` - Detailed requirements
- [ ] `docs/user-guides/customer-app.md` - Customer app guide
- [ ] `docs/user-guides/store-portal.md` - Store portal guide

### Scripts
- [ ] `scripts/setup.sh` - Project setup automation
- [ ] `scripts/deploy.sh` - Deployment automation
- [ ] `.env.example` - Root environment variables template

## Recommended Next Steps

1. **Initialize Version Control**
   ```bash
   git init
   git add .
   git commit -m "Initial project structure"
   ```

2. **Setup Backend**
   - Initialize Node.js project
   - Install dependencies (Express, TypeScript, etc.)
   - Configure database connection
   - Implement basic API structure

3. **Setup Mobile**
   - Initialize Flutter project
   - Configure Android/iOS settings
   - Setup state management
   - Create basic app structure

4. **Setup Web**
   - Initialize React/Vue project
   - Install dependencies
   - Configure routing
   - Create basic layout

5. **Setup Infrastructure**
   - Create Docker development environment
   - Setup CI/CD pipelines
   - Configure cloud resources

6. **Documentation**
   - Define API contracts
   - Create architecture diagrams
   - Write technical specifications

## Development Workflow

1. **Feature Development**
   - Create feature branch
   - Implement feature in relevant module
   - Write tests
   - Update documentation
   - Create pull request

2. **Testing**
   - Unit tests for all modules
   - Integration tests for APIs
   - E2E tests for critical flows
   - UAT/SIT before production

3. **Deployment**
   - Development → Staging → Production
   - Automated CI/CD pipelines
   - Blue-green deployment strategy
   - Rollback capability

## Conventions

### Naming
- **Files:** kebab-case (e.g., `order-service.ts`)
- **Classes:** PascalCase (e.g., `OrderService`)
- **Variables:** camelCase (e.g., `orderDetails`)
- **Constants:** UPPER_SNAKE_CASE (e.g., `API_BASE_URL`)

### Git Branches
- `main` - Production code
- `develop` - Development code
- `feature/*` - New features
- `bugfix/*` - Bug fixes
- `hotfix/*` - Production hotfixes

### Commit Messages
```
type(scope): description

[optional body]

[optional footer]
```

Types: feat, fix, docs, style, refactor, test, chore

---

**Created:** 2025-12-24
**Version:** 1.0.0
**Status:** Project initialized
