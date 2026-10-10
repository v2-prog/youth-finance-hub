# Australian Youth Financial Literacy & Economic Empowerment Hub

Educational prototype for young Australians (approx. 15–34). Companion to the coeconomics.com Structure Lab.

## Features
- 12 interconnected learning rooms covering personal finance + structural/collective economic capability
- Progress tracking (localStorage only — no personal data collected)
- Glossary, support directory, educational disclaimer
- Mobile-first, accessible, Australian English, AUD, plain language
- All major claims linked to official Australian sources (Moneysmart/ASIC, ATO, Services Australia, ACNC, BCCM, National Debt Helpline, etc.)

## Important Notes
- **Educational only.** Not personalised financial, tax, legal or investment advice.
- Laws, thresholds, eligibility and rates change. Always verify against current official sources.
- Content framework last reviewed October 2026. Professional review recommended before formal educational use.

## Deployment (GitHub → Cloudflare Pages for coeconomics.com or subdomain)

1. Repository: https://github.com/v2-prog/youth-finance-hub
2. In Cloudflare Pages:
   - Connect this GitHub repository.
   - Framework preset: None (static).
   - Build command: (leave blank)
   - Build output directory: `/`
3. Attach custom domain (e.g. youth.coeconomics.com or update coeconomics.com) once DNS is on Cloudflare.

Note: index.html and styles.css are already committed. Upload or push script.js and content.js to complete the app (full files available from the previous local build).

## Local preview
Open `index.html` in a browser after all files are present, or use a simple local server.

## Content Governance
- Review tax, super, HECS-HELP, Centrelink and housing rules at least annually or when major legislation changes.

## Licence / Use
Prototype created for educational purposes. Adapt and extend as needed for Australian youth education, community organisations or schools.
