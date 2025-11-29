ROOTED — Arts & Culture Vertical

DISCOVERY_RULES.md

This document defines exact, enforceable discovery logic for the Arts & Culture vertical.
Discovery controls:

Maps

Search

Feeds

Trails

Seasonal overlays

Kids Mode visibility

If content does not satisfy discovery rules → it does not appear, regardless of who created it.

1. Global Discovery Doctrine (Inherited from ROOTED Core)

All Arts & Culture discovery obeys these immutable Core rules:

✅ Region-scoped (no cross-region bleed unless explicitly granted)

✅ Role-filtered

✅ Kids Mode hard-gated

✅ Seasonal overlays are additive, never exclusive

✅ No paid ranking overrides civic integrity

✅ Audit visibility for all promoted or featured assets

2. Discovery Surfaces Defined

Arts & Culture content may appear on:

Maps

Search results

Home feed

Vertical spotlight feed

Event calendars

Cultural trails

Kids Mode discovery layer

Each surface applies different filtering logic.

3. Base Eligibility Rules (All Surfaces)

An Arts & Culture asset (provider, event, program, landmark, trail, or resource) is eligible for discovery only if:

✅ Linked to a valid:

cultural_provider, cultural_event, cultural_program, cultural_landmark, cultural_trail, or cultural_resource

✅ Has a valid region_id

✅ Is NOT:

Soft-deleted

Admin-hidden

Under emergency suspension

✅ Passes:

Youth safety classification

Civic protection checks (if landmark/institutional)

If any of the above fails → discovery = DENIED.

4. Map Discovery Rules
4.1 What Appears on the Map

✅ Cultural providers (venues, artists with physical presence)

✅ Active cultural events

✅ Cultural landmarks

✅ Trail nodes (via opt-in trail overlay)

4.2 Map Filtering Layers

Users may filter by:

Provider type (artist, gallery, museum, etc.)

Discipline / genre

Audience (family, general, 18+)

Accessibility tags (ADA, sensory-friendly, ASL)

Seasonal relevance

Institution vs private venue

4.3 Absolute Map Exclusions

❌ Draft programs or events

❌ 18+ content in Kids Mode

❌ Unverified providers marked as “official”

❌ Protected landmarks marked as monetized

5. Search Discovery Rules

Search results respect:

Region

Role

Kids Mode

Publication state

Safety classification

5.1 Guest Search

Guests may search only:

Public providers

Public events

Public landmarks

Public trails

No contact data, no inquiries, no registration actions.

5.2 Individual Search

Individuals may:

Search all public content

Filter by:

Family-safe

Programs vs events vs landmarks

Save results

Register where allowed

5.3 Vendor & Institution Search

Vendors & institutions may additionally:

See open cultural_program_requests

Preview proposal competition counts (anonymized)

Discover collaboration opportunities

6. Feed Discovery Rules
6.1 Home Feed (General ROOTED Feed)

Arts & Culture appears only if:

User has:

Followed Arts & Culture category

Followed a cultural provider/institution

Or:

The content is regionally featured by admin

No algorithmic outrage, no dark engagement sorting.

6.2 Arts & Culture Spotlight Feed

A dedicated vertical feed showing:

Verified provider highlights

Seasonal events & programs

Cultural trails

Heritage / community features (opt-in overlays only)

Spotlight placement is:

✅ Curated

✅ Logged

❌ Never auto-sold

❌ Never auction-ranked

7. Event Calendar Discovery

Events appear in calendar views only if:

✅ Event is:

Published

Region-valid

Not suspended

✅ Arts & Culture overlay exists

✅ Youth classification is present

Calendar filtering includes:

Date range

Venue type

Audience

Season

Accessibility

8. Cultural Trail Discovery

Trails appear only if:

✅ Authored by institution or admin

✅ Passed Kids Mode safety review (if children allowed)

✅ All nodes are:

Valid

Public

Region-consistent

Trail nodes inherit discovery restrictions from their source entities.

9. Kids Mode Discovery Rules (Hard Gates)

In Kids Mode:

✅ Only content with:

kids_mode_visible = true

AND youth_safety_class = kids_safe

✅ Only:

Libraries

Family museums

Youth workshops

Public landmarks marked kids-safe

❌ No:

18+ programs

Paid ticketing

Donations

Messaging

Community reviews

Ads

If any uncertainty exists → the content is automatically hidden.

10. Seasonal Discovery Logic

Seasonal overlays:

✅ Modify prioritization

❌ Never override safety

Examples:

Summer:

Outdoor festivals promoted

Winter:

Indoor workshops surfaced

School year:

After-school programs prioritized

Seasonal systems may suggest but never auto-publish.

11. Cultural Overlay Discovery (Opt-In Only)

Users may opt into:

Heritage month highlights

Language-specific browsing

Community cultural spotlights

Defaults:

✅ Neutral

❌ No forced religious framing

❌ No demographic targeting without consent

12. Verification & Trust Impact on Discovery
Status	Discovery Impact
Verified provider	May be featured
Unverified provider	Public but never featured
Flagged provider	Hidden from spotlight
Under investigation	Soft-hidden from Kids Mode
False verification	Immediate suppression

Verification improves visibility, not access rights.

13. Civic Asset Discovery Protection

Protected civic assets:

✅ Always discoverable

❌ Never paywalled

❌ Never boosted via paid ranking

❌ Never sold as private experiences

Any attempt to bypass this triggers an admin audit event.

14. Failure & Degradation Rules

If discovery services fail:

✅ Fallback to:

Chronological sorting

Region-only filters

❌ Never fallback to:

Global unfiltered content

Unsafe Kids Mode exposure

If seasonal engine fails:

✅ Default to non-seasonal discovery

❌ Do not inject guessed seasonal data

15. Canonical Status

✅ Region-locked discovery
✅ Kids Mode fail-closed
✅ Civic asset protection enforced
✅ No pay-to-play exposure
✅ No dark algorithms
✅ Seasonality is additive, not coercive
✅ Fully compatible with ROOTED Core doctrine
