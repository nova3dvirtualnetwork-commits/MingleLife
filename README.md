Virtual World Platform
A cross-platform 3D virtual social world designed to grow with its users through an Age Progression System (APS), while maintaining strict separation between teen and adult environments.

Vision
Virtual World Platform is a persistent 3D social universe where users can create avatars, build homes, participate in communities, develop businesses, and socialize within age-appropriate environments.

The platform is designed around three core principles:

Safety First
User Ownership and Identity Continuity
Age-Appropriate Experiences
Unlike traditional virtual worlds, users may begin their journey as teenagers and continue into adulthood without creating a new account, while preserving strict safety boundaries throughout the process.

Key Features
Cross-Platform Support
Desktop
Mobile
Future VR support
Persistent Virtual Identity
Users keep:

Username
Avatar identity
Home ownership
Marketplace purchases
Virtual achievements
throughout their platform journey.

Age Progression System (APS)
The Age Progression System automatically manages user transitions between age environments.

Example:

Age 13
   ↓
Teen Environment
   ↓
Turns 18
   ↓
Adult Verification
   ↓
Adult Environment Access
No new account is required.

Environment Architecture
The platform consists of two independent social environments.

Teen Environment (13–17)
A highly protected area focused on social interaction, creativity and exploration.

Features
Age-appropriate avatar customization
Teen-only social spaces
Teen-only housing
Teen marketplace
Approved user-generated content
Enhanced moderation
Parent/guardian controls
Restrictions
No adult access
Restricted communication systems
No external contact sharing
Enhanced safety monitoring
Adult Environment (18+)
A fully featured virtual social world for verified adults.

Features
Expanded customization
Advanced housing
Marketplace economy
Creator monetization
Businesses and communities
Open social interaction
Safety
Community moderation
Reporting systems
Account protection
Fraud detection
Trust & Safety Architecture
The platform uses a layered moderation approach.

Layer 1 - AI Safety Engine
AI systems assist in:

Abuse detection
Grooming detection
Harassment detection
Scam detection
Behaviour analysis
Marketplace monitoring
AI does not make permanent enforcement decisions.

AI identifies potentially harmful activity for review.

Layer 2 - User Protection Tools
Every user has access to:

Report
Block
Mute
Ignore
Privacy controls
Reports automatically include relevant moderation evidence.

Layer 3 - Human Moderation
Moderators review:

Reports
Appeals
AI escalations
Serious incidents
Possible actions include:

Warning
Content removal
Temporary restrictions
Suspension
Permanent bans
Age Progression System (APS)
Purpose
The APS allows users to age naturally through the platform while preserving strict safety protections.

Life Cycle
Teen Account
      ↓
Turns 18
      ↓
Adult Eligibility
      ↓
Adult Verification
      ↓
Adult Activation
Transfers To Adult Environment
Allowed:

Username
Avatar identity
Eligible inventory
Home ownership
Purchased items
Achievements
Does Not Transfer
For safety reasons the following remain isolated:

Teen friendships
Teen direct messages
Teen groups
Teen social relationships
Teen moderation history
Users begin adult social experiences with a fresh social graph.

Environment Isolation
Teen and Adult realms are completely separated.

Prohibited Cross-Realm Actions
The platform prevents:

Cross-realm messaging
Cross-realm gifting
Cross-realm voice chat
Cross-realm friend requests
Cross-realm marketplace access
Access Control
All permissions are enforced server-side.

Clients never determine access rights.

Example:

User Realm = TEEN
Room Realm = ADULT

Access Denied
Technology Stack
Client
Unity 6
C#
Blender
Backend
Node.js
TypeScript
NestJS
Database
PostgreSQL
Authentication
Supabase Auth
Alternative Identity Provider
Multiplayer
Nakama (preferred)
Photon (alternative)
Storage
Cloudflare R2
CDN
Cloudflare
Monitoring
Sentry
Grafana
Proposed System Architecture
                 Unity Client
                       │
                       ▼
                 API Gateway
                       │
      ┌────────────────┼────────────────┐
      │                │                │
      ▼                ▼                ▼

Identity      Adult Services      Teen Services
APS Engine    Marketplace         Marketplace
Verification  Social Graph        Social Graph
              Housing             Housing

      │                │                │
      ▼                ▼                ▼

Identity DB     Adult Realm DB    Teen Realm DB
Database Overview
Identity Database
Stores:

Accounts
Authentication
Verification
Billing
APS records
Adult Database
Stores:

Adult avatars
Adult homes
Adult inventory
Adult friendships
Adult messages
Teen Database
Stores:

Teen avatars
Teen homes
Teen inventory
Teen friendships
Teen messages
Virtual Housing System
Every user may own one or more properties.

Supported features:

Furniture placement
Home customization
Asset ownership
Persistent layouts
Example:

{
  "itemId": "chair_001",
  "position": [12, 0, 3],
  "rotation": [0, 90, 0]
}
Avatar System
Modular avatar design:

Body
Hair
Eyes
Clothing
Accessories
Animations
Each asset contains:

Asset ID
Realm ID
Owner
Creator
Approval Status
Marketplace
Separate marketplaces exist for each realm.

Teen Marketplace
Approved content only
Manual review pipeline
Age-appropriate assets
Adult Marketplace
Expanded creator freedom
Additional asset categories
Creator commerce tools
Privacy Commitments
The platform operates according to privacy-by-design principles.

We will:

Collect minimal data
Protect sensitive information
Use trusted age-assurance providers
Avoid storing identity documents whenever possible
Provide user transparency
Support account appeals
Development Roadmap
Phase 1 – Prototype (0-3 Months)
Goal:

Adult-only proof of concept

Features:

Account creation
Basic avatars
One social environment
Multiplayer movement
Text chat
Housing prototype
Phase 2 – Social Systems (3-6 Months)
Features:

Friends
Inventory
Furniture placement
Data persistence
Phase 3 – Marketplace Foundation (6-12 Months)
Features:

Creator system
Asset ownership
Economy foundations
Moderation tools
Phase 4 – APS Implementation (12-18 Months)
Features:

Realm architecture
Age verification
Account progression
Permission system
Phase 5 – Teen Environment (18-24 Months)
Features:

Teen world launch
Parent controls
Enhanced moderation
Independent content review
Mission Statement
Our goal is to create a persistent virtual universe that evolves with its members throughout life while maintaining strong privacy, age-appropriate experiences, and a culture of safety, creativity, and community.

The platform is built on the belief that users should be able to grow, create, socialize, and express themselves in a secure environment that respects both freedom and responsibility.
