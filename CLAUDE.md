# CLAUDE.md - PICK-ME-UP Project

## Project Overview

**Project Name:** PICK-ME-UP
**Type:** AI-Powered Coffee Pick-up Platform
**Development Company:** Digitalmedia Outsource Solution Co., Ltd. (DOS)
**Last Updated:** 2025-12-24

## Project Description

PICK-ME-UP is an AI work team-powered coffee pick-up platform designed to streamline the coffee ordering and pickup process at physical stores. The system leverages AI agents to manage various aspects of the customer journey, from order placement to pickup coordination.

## Business Context

### Company Information
- **Developer:** Digitalmedia Outsource Solution Co., Ltd.
- **Brand:** DOS (We are DOS_)
- **Experience:** 10+ years, 100+ projects, 30+ team members
- **Expertise:** E-Commerce, Food Delivery & Logistics, Customer Loyalty systems
- **Tech Focus:** Mobile & Web applications, Cloud architecture, AI Integration

### Leadership Team
- **Jakapong (TLE)** - Chief Operating Officer
- **Nitipong (OHM)** - Head of Design
- **Surasee (PECK)** - Head of Infrastructure
- **Wasin (GIFT)** - Head of Developer

## Technical Stack Recommendations

### Frontend
- **Mobile App:** Flutter (cross-platform) or Swift (iOS) / Kotlin (Android)
- **Web Portal:** React or Vue.js
- **UI Framework:** Material Design or custom design system

### Backend
- **Runtime:** Node.js
- **Framework:** Express.js or NestJS
- **Database:** Firebase Firestore or PostgreSQL
- **Cloud Platform:** Google Cloud Platform or AWS

### AI & Integration Services
- **AI/ML:** Claude AI (Anthropic), custom AI agents
- **Push Notifications:** OneSignal or Firebase Cloud Messaging
- **Maps/Location:** Google Maps API
- **Payment:** Stripe, OPN, or 2C2P
- **Real-time Updates:** Firebase Realtime Database or Pusher
- **Search:** Algolia (for menu/store search)

### DevOps
- **CI/CD:** GitHub Actions or GitLab CI
- **Containerization:** Docker
- **Monitoring:** Google Cloud Monitoring or AWS CloudWatch

## Core Features

### Customer-Facing Features
1. Browse coffee menus from nearby stores
2. Place orders with customization options
3. AI-assisted order recommendations
4. Real-time order status tracking
5. Estimated pickup time notifications
6. Digital payment integration
7. Loyalty rewards program
8. Order history and favorites

### Store-Facing Features
1. Order management dashboard
2. Inventory management
3. Menu customization
4. Analytics and reporting
5. Customer communication tools
6. Queue management system

### AI Work Team Components
1. **Order Processing Agent** - Validates and processes customer orders
2. **Inventory Agent** - Monitors stock levels and availability
3. **Notification Agent** - Manages customer communications
4. **Queue Optimization Agent** - Optimizes pickup timing
5. **Recommendation Agent** - Provides personalized suggestions
6. **Analytics Agent** - Generates insights and reports

## Development Methodology

Following DOS standard agile process:
1. NDA and Contract Signing
2. Requirements Gathering
3. Kickoff Meeting
4. Design Phase
5. Development (Agile Sprints)
6. UAT/SIT Testing
7. Go-Live
8. Support (90-day warranty)

## Project Structure

```
Pick-me-up/
├── docs/                      # Documentation
│   ├── api/                   # API documentation
│   ├── architecture/          # System architecture diagrams
│   ├── business/              # Business requirements
│   └── user-guides/           # User manuals
├── backend/                   # Backend services
│   ├── src/
│   │   ├── agents/           # AI agents
│   │   ├── api/              # REST/GraphQL APIs
│   │   ├── config/           # Configuration
│   │   ├── models/           # Data models
│   │   ├── services/         # Business logic
│   │   └── utils/            # Utilities
│   ├── tests/                # Backend tests
│   └── package.json
├── mobile/                    # Mobile application
│   ├── android/              # Android-specific
│   ├── ios/                  # iOS-specific
│   ├── lib/                  # Flutter source
│   │   ├── features/         # Feature modules
│   │   ├── shared/           # Shared components
│   │   └── core/             # Core utilities
│   └── test/                 # Mobile tests
├── web/                       # Web application
│   ├── src/
│   │   ├── components/       # React/Vue components
│   │   ├── pages/            # Page components
│   │   ├── services/         # API services
│   │   ├── store/            # State management
│   │   └── utils/            # Utilities
│   └── public/               # Static assets
├── infrastructure/            # DevOps & Infrastructure
│   ├── docker/               # Docker configurations
│   ├── kubernetes/           # K8s manifests
│   └── terraform/            # Infrastructure as Code
├── shared/                    # Shared code/types
│   ├── types/                # TypeScript types
│   └── constants/            # Shared constants
└── scripts/                   # Build/deploy scripts
```

## Coding Standards

### General Guidelines
- **Languages:** TypeScript (preferred), Thai/English bilingual support
- **Code Style:** Follow enterprise-grade standards
- **Testing:** Comprehensive unit and integration tests
- **Documentation:** JSDoc/TSDoc for all public APIs
- **Version Control:** Git with feature branching

### Mobile Development
- Follow platform-specific guidelines (iOS HIG, Material Design)
- Mobile-first approach
- Offline-first architecture where applicable
- Optimize for performance and battery life

### Backend Development
- RESTful API design or GraphQL
- Proper error handling and logging
- Security best practices (OWASP Top 10)
- API versioning
- Rate limiting and authentication

### AI Agent Development
- Clear agent responsibilities and boundaries
- Proper error handling and fallbacks
- Logging and monitoring
- Performance optimization
- Ethical AI considerations

## Environment Setup

### Development
- Local development with hot-reload
- Mock data for testing
- Development Firebase/Cloud project

### Staging
- Pre-production testing environment
- Matches production configuration
- UAT/SIT testing

### Production
- High availability setup
- Auto-scaling configuration
- Production monitoring and alerts

## Security Considerations

1. **Authentication:** OAuth 2.0, Social login integration
2. **Data Protection:** Encryption at rest and in transit
3. **Payment Security:** PCI DSS compliance
4. **API Security:** JWT tokens, rate limiting
5. **Privacy:** PDPA compliance (Thai data protection)

## Performance Requirements

- API response time: < 200ms (p95)
- Mobile app startup: < 2 seconds
- Real-time updates: < 1 second latency
- 99.9% uptime SLA
- Support 10,000+ concurrent users

## Localization

- Primary: Thai language
- Secondary: English
- RTL support: Not required
- Currency: Thai Baht (THB)
- Date/Time: Thai timezone (UTC+7)

## Contact & Support

**Project Owner:** Jakapong Lomvong (TLE)
**Email:** jakapong@digitalmedia.co.th
**Phone:** +66 88-622-2488

**Company:** Digitalmedia Outsource Solution Co., Ltd.
**Address:** 91/11 Moo 2, Banmai, Pak Kret, Nonthaburi, TH 11120
**Tax ID:** 0105555063821

## References

- **Company Portfolio:** application.in.th
- **Company Website:** digitalmedia.co.th
- **Similar Projects:** Foodhunt (CRG), CPAC Delivery

## Notes for AI Development Tools

### When Working on This Project:
1. **Language Support:** Implement Thai language throughout the application
2. **Enterprise Quality:** Follow DOS enterprise-grade standards
3. **Mobile-First:** Prioritize mobile user experience
4. **Cloud-Native:** Design for cloud deployment (GCP/AWS)
5. **Testing:** Include comprehensive UAT/SIT test plans
6. **AI Integration:** Leverage Claude AI for intelligent agent behaviors
7. **Scalability:** Design for growth and high traffic
8. **Payment Integration:** Support Thai payment methods
9. **Real-time Features:** Implement real-time order tracking
10. **Analytics:** Build in comprehensive analytics from day one

### Development Priorities:
1. Core ordering flow (customer + store)
2. AI agent integration for order processing
3. Real-time notifications
4. Payment integration
5. Loyalty program
6. Advanced AI features (recommendations, optimization)

---

**Version:** 1.0.0
**Status:** Initial Setup
**Next Steps:** Requirements gathering and system design
