# Portfolio Grid Content Specification

- 10 portfolio items, displayed in a 4-4-2 grid (3 rows: 4 columns, 4 columns, 2 columns centered)
- Each item includes:
  - Title
  - Short summary (caption)
  - Technologies/platforms (caption)
  - Modal link (for details)
  - Portfolio image (400x289 for grid)
- Each item links to a modal with detailed info
- Items are ordered as shown below
- Real portfolio images used: img/portfolio/[name].png
- Third row items are centered with empty columns for spacing

# Layout Structure

- **Row 1 (4 items)**: Change Data Capture, Communication Compliance, Customer Inbox, Construction Punchlist
- **Row 2 (4 items)**: Event Notification Platform, Generative AI Tools, CI/CD Library, Infrastructure Reference Library
- **Row 3 (2 items, centered)**: Codefall, Blackjack Trainer

# Navigation

- Portfolio section accessible via main navigation menu item "Portfolio" (#portfolio)

# Example Item Structure

- Title: Change Data Capture Event Publisher
- Caption: ETL, SQL Server, AWS
- Image: img/portfolio/cep.png
- Modal: #portfolioModal1

# Modal Content Specification

- Each modal includes:
  - Title
  - Clever summary/intro
  - Large portfolio image (1200x800)
  - List of details:
    - Platform
    - Technologies
    - Highlights
    - Inspiration/business use case
    - Links to demo/info/source (if available)
    - Project date (if available)
- Real content for active projects, minimal placeholder for future items

# Current Portfolio Items (10 total)

## Row 1

### 1. Change Data Capture Event Publisher
- Grid image: `img/portfolio/cep.png`
- Modal image: `img/portfolio/cep.png`
- Caption: ETL, SQL Server, AWS
- Summary: ETL process multicasting tens of millions of change data capture events daily. Uses a custom "greedy" queue worker for maximum throughput across multiple threads and application instances.
- Platform: Windows Server, SQL Server, AWS
- Technologies: Service Broker Queues, Dataflow TPL
- Highlights: Dashboards built on custom telemetry, built-in retry and event poison logic
- Inspiration: Lower load on DB server by replacing dozens of change tracking queues with one
- Source code: Proprietary

### 2. Communication Compliance Engine
- Grid image: `img/portfolio/compliance.png`
- Modal image: `img/portfolio/compliance.png`
- Caption: CRM, Compliance, AWS
- Summary: CRM compliance calculator for determining when users can and cannot send their customers communications.
- Platform: AWS ECS, SNS, SQS, DynamoDB
- Technologies: Well-structured app code, extensive tests
- Highlights: Auto-refresh of compliance as data expires from the system
- Inspiration: Helping users avoid legal issues with customers
- Source code: Proprietary

### 3. Customer Inbox
- Grid image: `img/portfolio/inbox.png`
- Modal image: `img/portfolio/inbox.png`
- Caption: CRM, Messaging, React
- Summary: Modern communication front-end for managing CRM communications across all channels including email, SMS/MMS, and click-to-call.
- Platform: AWS S3, CloudFront, ECS, Elasticache
- Technologies: React with hooks, aspnetcore, SignalR
- Highlights: Real-time updates via websockets, support for media attachments
- Inspiration: A modern UI built to order
- Source code: Proprietary

### 4. Construction Punchlist Mobile App
- Grid image: `img/portfolio/punchlist.png`
- Modal image: `img/portfolio/punchlist.png`
- Caption: Mobile, Cordova, Offline
- Summary: A streamlined mobile app for managing construction punchlists in the field. Enables teams to track, update, and resolve project issues efficiently with real-time collaboration and a user-friendly interface.
- Platform: Web & Mobile
- Technologies: Apache Cordova, Angular, SQLite
- Highlights: Photo attachments, real-time updates, mobile-first design, offline sync
- Inspiration: Simplify and digitize construction site issue tracking
- Source code: Proprietary

## Row 2

### 5. Cloud-native Event Notification Platform
- Grid image: `img/portfolio/eventing.png`
- Modal image: `img/portfolio/eventing.png`
- Caption: AWS, EventBridge, Serverless
- Summary: A fully cloud native pub-sub hub built on AWS for reliably processing millions of daily notification events to internal and external subscribers.
- Platform: AWS API Gateway, EventBridge
- Technologies: Terraform, Node.js
- Highlights: Fully serverless design, cost minimizing architecture
- Inspiration: Provide a one-stop shop for event ingestions and publication
- Source code: Proprietary

### 6. Generative AI Communication Tools
- Grid image: `img/portfolio/genai.png`
- Modal image: `img/portfolio/genai.png`
- Caption: AI, CRM, Python
- Summary: Integrated AI tooling for CRM customers. Custom prompts based on known customer data points to help users create crafted communication content.
- Platform: AWS ECS Fargate containers
- Technologies: AWS Bedrock, Python, aspnetcore
- Highlights: Custom prompt templates, cost tracking and reporting
- Inspiration: You either adopt AI or you seal your fate
- Source code: Proprietary

### 7. CI/CD Shared Component Library
- Grid image: `img/portfolio/ci-cd.png`
- Modal image: `img/portfolio/ci-cd.png`
- Caption: GitHub, CI/CD, Automation
- Summary: Shared Github actions and workflows for standard pipeline tooling across the organization. Self-hosted runners for various platform needs.
- Platform: Github
- Technologies: YAML, Node/JavaScript, containers
- Highlights: Integrations with various enterprise concerns like change tracking and security systems
- Inspiration: Consolidating pipelines and ensuring consistency
- Source code: Proprietary

### 8. Infrastructure Reference Library
- Grid image: `img/portfolio/infra.png`
- Modal image: `img/portfolio/infra.png`
- Caption: Docs, Reference, Internal
- Summary: A centralized knowledge base for internal tools, processes, and best practices. Ensures consistency and efficiency across the organization.
- Platform: Internal Wiki
- Technologies: Markdown, Git, Static Site Generator
- Highlights: Version-controlled documentation, easy navigation, search functionality
- Inspiration: A single source of truth for internal references
- Source code: Proprietary

## Row 3 (Centered)

### 9. Codefall
- Grid image: `img/portfolio/codefall.png`
- Modal image: `img/portfolio/codefall.png`
- Caption: Thumby, MicroPython, Graphics
- Summary: A mesmerizing "Matrix rain" animation for the Thumby handheld. Features layered depth, dynamic glyph morphing, and interactive controls for speed, density, and freezing the code. Custom fonts and optimized pixel rendering deliver a smooth, visually rich experience on limited hardware.
- Platform: Thumby (tiny handheld game console)
- Technologies: MicroPython, custom pixel rendering, original glyph/font design
- Highlights: Animated title screen, real-time controls, five depth layers, and multiple glyph sets
- Inspiration: The iconic digital rain from The Matrix
- [Live Demo & Info](https://anewcomer.github.io/codefall/)
- [Source Code](https://github.com/anewcomer/codefall)

### 10. Blackjack Trainer
- Grid image: `img/portfolio/blackjack.png`
- Modal image: `img/portfolio/blackjack.png`
- Caption: React, TypeScript, Web
- Summary: An interactive web app for mastering blackjack basic strategy. Practice with real-time feedback, strategy charts, and session analytics. Supports multi-hand play, advanced rules, and accessibility features for all devices.
- Platform: Web (desktop, tablet, mobile)
- Technologies: React, TypeScript, Redux Toolkit, Material-UI, Jest, Playwright
- Highlights: Real-time strategy feedback, multi-hand support, session analytics, exportable data, keyboard shortcuts, dark/light themes
- Inspiration: Make learning optimal blackjack strategy engaging and accessible
- [Live Demo](https://anewcomer.github.io/blackjack-trainer/)
- [Source Code](https://github.com/anewcomer/blackjack-trainer)
