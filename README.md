# Reserve Journeys - Landing Page Redesign

## Overview
The website has been completely redesigned from a trip-listing platform to a tiered engagement model. The new structure features:

- **New Landing Page** (index.html) - Welcome page showcasing 4 engagement tiers
- **4 Tier Subpages** - Each with detailed information and inquiry system
- **Inquiry Modal** - Popup form on each tier page to capture customer inquiries

## File Structure

### Core Pages
- `index.html` - Landing page with 4 tier cards (REDESIGNED)
- `tier-1-destination-discovery.html` - Tier 1: Initial consultation tier
- `tier-2-bespoke-itinerary.html` - Tier 2: Custom itinerary planning
- `tier-3-journey-embarkment.html` - Tier 3: Full-service travel management
- `tier-4-exclusive-hosted.html` - Tier 4: Luxury hosted group journeys

### Legacy Pages (Still Available)
- `trip.html` - Trip details & booking (legacy, still functional)
- `booking.html` - Booking confirmation (legacy, still functional)
- `reserve-journeys-artifact.html` - Artifact file

## Design Features

### Consistent Design
- All pages use the same color palette and styling
- Common header with "Back to All Tiers" navigation
- Responsive grid layouts
- Smooth hover effects and animations

### Each Tier Page Includes
1. **Hero Section** - Tier title and value proposition
2. **What You Get** - Highlight cards with 4 key features
3. **Perfect For** - Target audience description
4. **The Process** - Step-by-step explanation
5. **Inquiry Modal** - Popup form for customer inquiries
6. **Consistent Footer** - Copyright information

### Inquiry Form Features
- Name, email, phone fields
- Custom textarea for "What are you looking for?"
- Client-side form handling with console logging
- Success message and form reset
- Click outside modal to close

## Color Scheme (Maintained)
- Background: `#e8e2d8`
- Surface: `#f4efe6`
- Surface Dark: `#1e3020`
- Accent: `#6e1e2e`
- Accent Soft: `#c45a70`
- Text: `#1e3020`

## Navigation Flow
```
index.html (Landing)
├── tier-1-destination-discovery.html
├── tier-2-bespoke-itinerary.html
├── tier-3-journey-embarkment.html
└── tier-4-exclusive-hosted.html

All tier pages link back to: index.html
```

## Engagement Tiers

### Tier 1: Destination Discovery Consultation
- Expert destination recommendations
- Travel style assessment
- Budget-conscious planning
- Initial exploration consultation

### Tier 2: Bespoke Itinerary Development
- Custom itinerary design
- Accommodation curation
- Activity & experience recommendations
- Ongoing planning support

### Tier 3: Journey Embarkment
- Complete trip coordination
- 24/7 travel support
- Premium accommodations
- Concierge services

### Tier 4: Exclusive Hosted Journeys
- Expert host accompaniment
- Curated group experiences
- Luxury accommodations
- Insider access & exclusive experiences

## Next Steps (Recommendations)

1. **Backend Integration** - Connect inquiry forms to email/database
2. **Inquiry Tracking** - Store inquiries in a database for follow-up
3. **Admin Dashboard** - Dashboard to view and manage inquiries
4. **Email Notifications** - Auto-send confirmation emails to inquirers
5. **CRM Integration** - Connect with CRM system for lead management

## Notes
- All inquiries currently log to browser console (client-side only)
- To save inquiries, connect the `submitInquiry()` function to a backend API
- Modal closes by clicking the X, the Submit button, or clicking outside
- All pages are fully responsive and mobile-friendly
