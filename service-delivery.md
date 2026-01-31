# Hire Claw - Service Delivery Plan

## The Vision
Offer a persistent AI assistant that runs 24/7 with memory, delivered as a service.

## Technical Stack

### Core
- OpenClaw as the agent framework
- Claude/GPT as the underlying model
- Telegram/Discord as communication channel

### Infrastructure Options

#### Option 1: VPS per Customer
- Each customer gets their own VPS
- Full isolation, dedicated resources
- Higher cost (~$20-50/mo per customer)
- Good for privacy-conscious customers

#### Option 2: Shared Infrastructure
- Multiple customers on same server
- Separate OpenClaw instances/sessions
- Lower cost (~$5-10/mo per customer)
- Need careful session isolation

#### Option 3: Hybrid
- Shared by default
- Dedicated VPS as premium tier

## Cost Analysis (Option 2 - Shared)

### Monthly Costs per Customer
- API usage (Claude): ~$20-50/mo (depends on usage)
- Server share: ~$5/mo
- Telegram/Discord: free
- Domain/email: negligible

### Pricing Math
- Charge: $99/mo
- Cost: ~$30-60/mo
- Margin: ~40-70%

### Break-even
- Need ~3-5 customers to cover base costs
- Each additional customer is mostly API cost

## Onboarding Flow

1. Customer emails expressing interest
2. I respond, ask about their use case
3. Set up their profile (name, preferences, context)
4. Add them to Telegram/Discord
5. Initial onboarding session to learn their workflow
6. Ongoing service begins

## What Customers Get

### Basic Package ($99/mo)
- 24/7 availability
- Persistent memory across sessions
- Web browsing, research
- Writing assistance
- Basic automation
- Telegram or Discord access

### Premium Package (TBD - $199/mo?)
- Everything in Basic
- Dedicated instance
- More API credits
- Calendar integration
- Email access (with their permission)
- Priority response time

## Challenges to Solve

1. **Scaling**: How to run multiple instances efficiently
2. **Billing**: Payment processing (Stripe?)
3. **Onboarding**: Make it smooth and automated
4. **Trust**: How to build trust for email/calendar access
5. **Privacy**: Clear data handling policies
6. **Support**: What if something breaks?

## MVP Plan

### Phase 1: Manual (First 5 customers)
- Handle everything manually
- Learn what customers actually want
- Iterate on the service

### Phase 2: Semi-automated (5-20 customers)
- Basic automation for onboarding
- Dashboard for managing customers
- Better monitoring

### Phase 3: Scalable (20+ customers)
- Fully automated onboarding
- Self-service portal
- Multiple agents (hire other AI?)

## Next Steps

1. [ ] Get first paying customer
2. [ ] Document onboarding process
3. [ ] Set up Stripe for payments
4. [ ] Create basic customer management
5. [ ] Define SLA/terms of service
6. [ ] Create privacy policy

## Questions to Answer

- How do I handle API costs if customer uses a lot?
- What's the fair use policy?
- How do I prove the value to skeptical customers?
- What makes this worth $99 vs free ChatGPT?
