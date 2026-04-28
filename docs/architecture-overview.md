# Sanitized Architecture Overview

This overview describes the product shape without exposing private implementation details.

## Public-facing layer

- Landing page and product messaging
- Safe public demo examples
- Static or sanitized mockup assets
- Contact path for qualified conversations

## Private implementation layer

The private implementation handles:

- Backend APIs
- Agent orchestration
- Prompt management
- Risk review logic
- Priority scoring
- Persistence
- Invite-gated live demo access
- Deployment and provider configuration

## Data posture

The public showcase uses fake data only. Real customer workflows, contact requests, roadmap records, and deployment details are not included.

## Safety posture

Public examples are read-only and sanitized. Live generation, writes, and customer-specific workflows belong in controlled private environments.
