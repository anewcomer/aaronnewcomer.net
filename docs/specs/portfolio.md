# Portfolio Grid Content Specification

- 12 portfolio items, displayed in a 3x4 grid (3 rows, 4 columns)
- Each item includes:
  - Title
  - Short summary (caption)
  - Technologies/platforms (caption)
  - Modal link (for details)
  - Placeholder image (400x289)
- Each item links to a modal with detailed info
- Items are ordered to match .prompts/portfolio.md
- Placeholder images used for now: https://placehold.co/400x289?text=Portfolio+N

# Example Item Structure

- Title: Change Data Capture Event Publisher
- Caption: ETL, SQL Server, AWS
- Image: https://placehold.co/400x289?text=Portfolio+1
- Modal: #portfolioModal1

# Modal Content Specification

- Each modal includes:
  - Title
  - Clever summary/intro
  - Large placeholder image (1200x800)
  - List of details:
    - Platform
    - Technologies
    - Highlights
    - Inspiration/business use case
    - Links to demo/info/source (if available)
    - Project date (if available)
- Placeholders for items without details

# Portfolio Items

## Change Data Capture Event Publisher
- Grid image: `https://placehold.co/400x289?text=Portfolio+1`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+1`
- Caption: ETL, SQL Server, AWS
- Summary: ETL process multicasting tens of millions of change data capture events daily. Uses a custom "greedy" queue worker for maximum throughput across multiple threads and application instances.
- Platform: Windows Server, SQL Server, AWS
- Technologies: Service Broker Queues, Dataflow TPL
- Highlights: Dashboards built on custom telemetry, built-in retry and event poison logic
- Inspiration: Lower load on DB server by replacing dozens of change tracking queues with one
- Source code: Proprietary

## Communication Compliance Engine
- Grid image: `https://placehold.co/400x289?text=Portfolio+2`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+2`
- Caption: CRM, Compliance, AWS
- Summary: CRM compliance calculator for determining when users can and cannot send their customers communications.
- Platform: AWS ECS, SNS, SQS, DynamoDB
- Technologies: Well-structured app code, extensive tests
- Highlights: Auto-refresh of compliance as data expires from the system
- Inspiration: Helping users avoid legal issues with customers
- Source code: Proprietary

## Customer Inbox
- Grid image: `https://placehold.co/400x289?text=Portfolio+3`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+3`
- Caption: CRM, Messaging, React
- Summary: Modern communication front-end for managing CRM communications across all channels including email, SMS/MMS, and click-to-call.
- Platform: AWS S3, CloudFront, ECS, Elasticache
- Technologies: React with hooks, aspnetcore, SignalR
- Highlights: Real-time updates via websockets, support for media attachments
- Inspiration: A modern UI built to order
- Source code: Proprietary

## Construction Punchlist Mobile App
- Grid image: `https://placehold.co/400x289?text=Portfolio+4`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+4`
- Caption: Mobile, Cordova, Offline
- Summary: A streamlined mobile app for managing construction punchlists in the field. Enables teams to track, update, and resolve project issues efficiently with real-time collaboration and a user-friendly interface.
- Platform: Web & Mobile
- Technologies: Apache Cordova, Angular, SQLite
- Highlights: Photo attachments, real-time updates, mobile-first design, offline sync
- Inspiration: Simplify and digitize construction site issue tracking
- Source code: Proprietary

## Cloud-native Event Notification Platform
- Grid image: `https://placehold.co/400x289?text=Portfolio+5`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+5`
- Caption: AWS, EventBridge, Serverless
- Summary: A fully cloud native pub-sub hub built on AWS for reliably processing millions of daily notification events to internal and external subscribers.
- Platform: AWS API Gateway, EventBridge
- Technologies: Terraform, Node.js
- Highlights: Fully serverless design, cost minimizing architecture
- Inspiration: Provide a one-stop shop for event ingestions and publication
- Source code: Proprietary

## Generative AI Communication Tools
- Grid image: `https://placehold.co/400x289?text=Portfolio+6`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+6`
- Caption: AI, CRM, Python
- Summary: Integrated AI tooling for CRM customers. Custom prompts based on known customer data points to help users create crafted communication content.
- Platform: AWS ECS Fargate containers
- Technologies: AWS Bedrock, Python, aspnetcore
- Highlights: Custom prompt templates, cost tracking and reporting
- Inspiration: You either adopt AI or you seal your fate
- Source code: Proprietary

## CI/CD Shared Component Library
- Grid image: `https://placehold.co/400x289?text=Portfolio+7`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+7`
- Caption: GitHub, CI/CD, Automation
- Summary: Shared Github actions and workflows for standard pipeline tooling across the organization. Self-hosted runners for various platform needs.
- Platform: Github
- Technologies: YAML, Node/JavaScript, containers
- Highlights: Integrations with various enterprise concerns like change tracking and security systems
- Inspiration: Consolidating pipelines and ensuring consistency
- Source code: Proprietary

## Codefall
- Grid image: `https://placehold.co/400x289?text=Portfolio+8`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+8`
- Caption: Thumby, MicroPython, Graphics
- Summary: A mesmerizing "Matrix rain" animation for the Thumby handheld. Features layered depth, dynamic glyph morphing, and interactive controls for speed, density, and freezing the code. Custom fonts and optimized pixel rendering deliver a smooth, visually rich experience on limited hardware.
- Platform: Thumby (tiny handheld game console)
- Technologies: MicroPython, custom pixel rendering, original glyph/font design
- Highlights: Animated title screen, real-time controls, five depth layers, and multiple glyph sets
- Inspiration: The iconic digital rain from The Matrix
- [Live Demo & Info](https://anewcomer.github.io/codefall/)
- [Source Code](https://github.com/anewcomer/codefall)

## Blackjack Trainer
- Grid image: `https://placehold.co/400x289?text=Portfolio+9`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+9`
- Caption: React, TypeScript, Web
- Summary: An interactive web app for mastering blackjack basic strategy. Practice with real-time feedback, strategy charts, and session analytics. Supports multi-hand play, advanced rules, and accessibility features for all devices.
- Platform: Web (desktop, tablet, mobile)
- Technologies: React, TypeScript, Redux Toolkit, Material-UI, Jest, Playwright
- Highlights: Real-time strategy feedback, multi-hand support, session analytics, exportable data, keyboard shortcuts, dark/light themes
- Inspiration: Make learning optimal blackjack strategy engaging and accessible
- [Live Demo](https://anewcomer.github.io/blackjack-trainer/)
- [Source Code](https://github.com/anewcomer/blackjack-trainer)

## Placeholder 1
- Grid image: `https://placehold.co/400x289?text=Portfolio+10`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+10`
- Caption: Coming soon
- Summary: Coming soon.

## Placeholder 2
- Grid image: `https://placehold.co/400x289?text=Portfolio+11`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+11`
- Caption: Coming soon
- Summary: Coming soon.

## Infrastructure Reference Library
- Grid image: `https://placehold.co/400x289?text=Portfolio+12`
- Modal image: `https://placehold.co/1200x800?text=Portfolio+12`
- Caption: Docs, Reference, Internal
- Summary: A centralized knowledge base for internal tools, processes, and best practices. Ensures consistency and efficiency across the organization.
- Platform: Internal Wiki
- Technologies: Markdown, Git, Static Site Generator
- Highlights: Version-controlled documentation, easy navigation, search functionality
- Inspiration: A single source of truth for internal references
- Source code: Proprietary
