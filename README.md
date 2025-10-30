# Porsche-sandbox
# Porsche Center Website Migration Demo
Porsche Website Migration
## Objective
Recreate four existing dealer pages using the new Porsche Center Website (PCW) layout, **without a CMS**, to demonstrate design consistency, content migration, and UX alignment.

## Deliverables
- `index.html` – Homepage (Champion Porsche)
- `about.html` – About Us (Porsche Downtown LA)
- `finance.html` – Finance Center (Porsche Austin)
- `service-spa.html` – Auto Spa Center (Porsche Monterey)
- `styles.css` – Shared styling
- This `README.md` – Approach and rationale

## Approach
1. **Analyzed PCW reference sites** (Salt Lake City, Las Vegas, North Atlanta) to extract a reusable component inventory: header, hero, cards, contact, and footer.  
2. **Inventoried source content** from the four dealer URLs, keeping evergreen descriptive copy and substituting static placeholders for dynamic feeds.  
3. **Mapped each content block** to a corresponding PCW component.  
4. **Built static HTML/CSS prototypes** emulating PCW’s grid, typography, spacing, and call-to-action hierarchy.  
5. **Ensured accessibility and responsiveness** for desktop and mobile.  
6. **Documented limitations**: no CMS, no live inventory integration, no dealer-specific scripts.

## Limitations
- Inventory search, live offers, and lead-form integrations are shown as static placeholders.  
- Images use generic stand-ins (`assets/offer1.jpg`, etc.).  
- Forms are non-functional; integration would occur within PCW’s Storyblok or internal platform later.

## Future State (When migrated to PCW)
- Each section maps 1-to-1 with PCW content types:
  - Hero → Hero Module  
  - Cards/Grid → Offer Tiles Component  
  - Hours/Address → Dealer Info Module  
  - Contact → Form Module  
- Content will become fully editable through Porsche’s CMS.

