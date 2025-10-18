# Create Professional v2 Website with Modern Design and Team Bios

## Assumptions
- Use existing copy from `index.html` as base content
- Apply professional color scheme: white background, dark grey text (#333333), light grey secondary text (#666666), blue accent (#337AB7)
- Team photos are available in `figures/` folder
- Maintain responsive design principles
- Keep existing logo and favicon from `figures/` folder
- Preserve all existing functionality and navigation

## Open Questions
Q1: What specific team member photos should be used? (A1: leon-pirogovsky.jpg, haim-nassir.jpg, boris-gorelik.jpg - respectively for Leon Pirogovsky, Haim Nassir, and Boris Gorelik)
Q2: Should the new design maintain the same layout structure or can it be reorganized? (A2: the current structure is not good, reorganize as needed to be more professional)
Q3: Any specific professional styling preferences beyond the color scheme? (A3: no)
Q4: Should the new version replace the existing files or coexist? (A4: coexist for now)

## Approach
Create a parallel version (v2) to allow comparison and gradual migration. Use modern CSS techniques with the professional color palette from the reference design. Focus on clean typography, generous whitespace, and subtle interactive elements.

## Steps

1. **Create `stylesv2.css` with professional color scheme**
   - Implement color variables: white background, dark grey text (#333333), light grey secondary (#666666), blue accent (#337AB7)
   - Design clean typography with sans-serif fonts
   - Add generous whitespace and modern spacing
   - Create subtle shadows and hover effects
   - Ensure responsive design for all screen sizes

2. **Create `indexv2.html` with existing copy structure**
   - Copy content from `index.html`
   - Link to `stylesv2.css` instead of inline styles
   - Update logo and favicon paths to `figures/` folder
   - Maintain all existing sections and navigation

3. **Enhance About section with team member bios**
   - Replace generic team section with specific member profiles
   - Add Leon Pirogovsky (CEO) bio with professional background
   - Add Haim Nassir (Chief Compliance Officer) bio with compliance expertise
   - Add Boris Gorelik, PhD (CTO) bio with technical background
   - Include team member photos from `figures/` folder
   - Format bios consistently with company-relevant highlights

4. **Apply professional styling to all sections**
   - Update hero section with clean, modern appearance
   - Style capability cards with subtle borders and shadows
   - Enhance business impact section with professional layout
   - Improve footer with clean, minimal design
   - Ensure consistent spacing and typography throughout

5. **Test responsive design and cross-browser compatibility**
   - Verify mobile responsiveness
   - Test on different screen sizes
   - Ensure logo and images display correctly
   - Validate HTML and CSS

## Scope and Non-Goals
**Included:**
- Complete redesign with professional color scheme
- Team member bios with photos
- Modern, clean styling
- Responsive design
- All existing content and functionality

**Excluded:**
- Backend functionality changes
- New features beyond styling
- Content changes beyond team bios
- Performance optimizations

## Requirements and Constraints
- Must maintain accessibility standards
- Must be responsive across all devices
- Must use existing logo and favicon files
- Must preserve all existing content
- Must follow modern web standards

## Verification & Acceptance Criteria
- Website displays with professional color scheme
- Team member bios are properly formatted and include photos
- All sections maintain clean, modern appearance
- Responsive design works on mobile and desktop
- No broken links or missing images
- HTML and CSS validate without errors

## Deliverables
- `indexv2.html` - New HTML file with professional styling
- `stylesv2.css` - Professional stylesheet with modern design
- Updated team section with member bios and photos
