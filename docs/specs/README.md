# index.html Content Specification

## 1. Head & Meta
- Title: Aaron Newcomer :: Software Matters
- Meta: charset, viewport, description, author
- CSS: Bootstrap, agency.css, Font Awesome, Google Fonts
- HTML5 shims for IE8 support

## 2. Navigation Bar
- Fixed-top Bootstrap navbar
- Brand: Aaron Newcomer (links to #page-top)
- Menu items:
  - Skills (#services)
  - About (#about)
  - Hats (#team)
  - Contact (#contact)
- Responsive collapse for mobile

## 3. Header
- Large intro section
- Lead-in: "My name is Aaron Newcomer."
- Heading: "It's Nice To Meet You."
- Button: "Tell Me More" (links to #services)

## 4. Skills/Services Section (#services)
- Section heading: Skills
- Subheading: Professional problem solving.
- 3 columns:
  - Web Applications: Modern JS frameworks, scalable, reliable data stores
  - Architecture & Design: Reliable, extensible, scalable, testable, maintainable
  - Enterprise Experience: 10+ years, Agile, Scrum, SOA, SaaS, CI/CD, PRs

## 5. Portfolio Grid Section (#portfolio)
- 12 items, 3 rows of 4 columns (see portfolio-grid-spec.md)
- Each item: title, caption, modal link, placeholder image
- Each item links to a modal with details

## 6. About Section (#about)
- Section heading: About
- Subheading: Historically important events.
- Timeline (ul.timeline):
  - 8 timeline items (li), alternating left/right
  - Each: image, heading (date, subheading), body (description)
  - Last item: "What will tomorrow bring?"

## 7. Team Section (#team)
- Section heading: Hats
- Subheading: I wear many hats. They cover my bald head.
- 3 team members:
  - Architect & Designer: img, name, tagline, social links (LinkedIn, Slack, Resume)
  - Code Monkey: img, name, tagline, social links (Stack Overflow, GitHub)
  - Communications Director: img, name, tagline, social links (Twitter, Email)
- Closing text: "When combined, they create a total greater than the sum of their parts..."

## 8. Contact Section (#contact)
- Section heading: Contact
- Subheading: Help me help you.
- Contact form: name, email, phone, message, submit button
- Uses Formspree for POST

## 9. Footer
- Copyright: AaronNewcomer.Net 2025

## 10. Portfolio Modals
- 12 modals, one per portfolio item (see portfolio-grid-spec.md)
- Each modal: title, summary, large placeholder image, details list, close button

## 11. Scripts
- jQuery, Bootstrap JS, plugin JS, custom JS (agency.js)
- Google Analytics snippet

## 12. Misc
- Clients aside (commented out)
- Social/quicklinks in footer (commented out)

---

# Example Section Structure

## Skills Section
- Section id: services
- Container > row > col-lg-12 (heading)
- Row > 3 col-md-4 (each with icon, heading, text)

## Portfolio Item
- See portfolio-grid-spec.md

## Timeline Item
- li > .timeline-image (img) + .timeline-panel (heading, body)

## Team Member
- .team-member > img + h4 + p + ul.social-buttons

## Contact Form
- form#contactForm > name, email, phone, message, submit

---

# Notes
- All sections use Bootstrap grid system
- Images are responsive
- Modals use Bootstrap modal classes
- Section ids match nav links
- Placeholder images used for portfolio
- Some sections (clients, social links) are commented out for future use
