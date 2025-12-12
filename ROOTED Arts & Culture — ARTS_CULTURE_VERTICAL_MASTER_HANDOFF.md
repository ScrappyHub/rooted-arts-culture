# ROOTED Arts & Culture — Master Handoff (UI + Backend Alignment)

Status: Documentation-complete  
Scope: Arts & Culture vertical UI  
Backend: Uses ROOTED Core events, providers, landmarks, seasonal engine  

If the app behavior and this document conflict → this document wins.

---

## 1. What Arts & Culture Is

A public-facing cultural discovery vertical including:

- Museums  
- Galleries  
- Heritage centers  
- Historic societies  
- Performing arts venues  
- Public art installations  

Arts & Culture is:

✅ Public  
✅ Educational  
❌ Commercial (beyond ticketing UI)  
❌ Political  
❌ Algorithmic  

---

## 2. Roles & Access

### Guest
May:
- Browse exhibits, events, venues  
- Use seasonal cultural filters  

May NOT:
- Post content  
- Message venues  
- Access analytics  

### Individuals
Same as guest, plus:
- Save favorites  
- Participate in workshops  

### Venues (Vendors)
Nonprofit or cultural orgs:

FREE:  
- Profile  
- Exhibit & event posting  

PREMIUM:  
- Featured placement (if governance allows)  
- Media expansion  

PREMIUM PLUS:  
- Priority event exposure (if governance allows)  

### Institutions
Used primarily for educational partnerships.

### Admin
Moderates cultural sensitivity, reviews venues, manages overlays.

---

## 3. Kids Mode (Arts & Culture)

Kids Mode shows:
- Museums  
- Family-friendly exhibits  
- Historical learning  
- Cultural heritage icons  
- Age-safe performances  

Kids Mode hides:
- Mature art  
- Political content  
- Religious content (unless parent unlocked)  
- Donation / fundraising  

---

## 4. Discovery Surfaces

- Venue discovery (6–8 cards)  
- Rotating museum/gallery set  
- Seasonal cultural overlays (heritage month, local festivals)  
- Category filters (visual arts, performance, history, etc.)  
- Historical landmark integration  

---

## 5. Event Types

Arts & Culture uses the same `events` table with:

- event_type = 'cultural_event'  
- event_vertical = 'ARTS_CULTURE'  

---

## 6. Launch Checklist

- Venue discovery working  
- Exhibit/event browsing  
- Kids Mode filtering  
- Seasonal overlays  
- UI polish  

---

END OF HANDOFF