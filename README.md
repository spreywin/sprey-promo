# Sprey Promo

**The public website of the Sprey ecosystem.**

[Website](https://www.sprey.win/) · [Processing](https://pay.sprey.win/) · [Documentation](https://docs.sprey.win/) · [GitHub](https://github.com/spreywin/sprey-promo)

## Overview

Sprey Promo is the public website for the Sprey ecosystem. It introduces our products, explains their purpose, and connects visitors with our services and documentation.

Our core product is **Sprey Processing**, cryptocurrency payment infrastructure built on BTCPay Server.

**Crypto Payments. Your Funds. Your Control.**

The project is developed as a lightweight website, with its content, design, and functionality maintained in this repository.

## Sprey Ecosystem

| Resource | Purpose |
|---|---|
| [Sprey Promo](https://www.sprey.win/) | Public website |
| [Sprey Processing](https://pay.sprey.win/) | Cryptocurrency payment service |
| [Registration](https://pay.sprey.win/register) | Free account registration |
| [Sprey Docs](https://docs.sprey.win/) | Canonical documentation and technical resources |\n| [Sprey Lab documentation](https://docs.sprey.win/products/sprey-lab/) | Experimental BTCPay applications and verified Lab test scenarios |
| [Sprey Store](https://sprey.win/store) | Store and additional offerings |

**Sprey Lab** is a separate experimental direction for prototypes and new product ideas, documented separately from the core Processing service. Lab test results do not automatically certify the same workflows for commercial Processing.

## Technology

The website uses:

- HTML5
- CSS
- JavaScript
- Tailwind CSS via CDN
- Google Fonts
- A third-party translation widget

The project is served as a static website. Its current implementation and dependencies should be checked in the source files rather than inferred from the original template.

## Project Structure

```text
sprey-promo/
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── img/
│   │   ├── brand.svg
│   │   ├── favicon.svg
│   │   ├── logo-mark.svg
│   │   ├── og-cover.png
│   │   └── og-cover.svg
│   └── js/
│       └── main.js
├── screenshot/
│   └── preview.png
├── index.html
├── package.json
└── README.md
```

## Deployment

The production website is hosted on Cloudflare Pages.

- **GitHub repository:** [spreywin/sprey-promo](https://github.com/spreywin/sprey-promo)
- **Production branch:** `main`
- **Production website:** [www.sprey.win](https://www.sprey.win/)

Changes pushed to the connected production branch are deployed through the Cloudflare Pages integration.

### Update workflow

1. Edit the required files in the local project.
2. Review the changes and check the affected website sections.
3. Check the Git working tree.
4. Commit and push the intended changes.
5. Confirm the Cloudflare deployment succeeds and inspect the live site when appropriate.

Example PowerShell commands:

```powershell
git status
git add README.md
git commit -m "Update Sprey Promo documentation"
git push origin main
```

Run the commands from the local project directory. Review `git status` before committing.

No local build command is documented here because the current `package.json` references a build script that is no longer present in the repository.

## Maintenance Principles

- Keep the content consistent with the actual Sprey products.
- Use English as the default website language.
- Keep navigation and links aligned with the current ecosystem.
- Remove obsolete template content and unused files when appropriate.
- Keep the website responsive and verify meaningful changes.
- Update this README when the project structure or deployment workflow changes.

## Original Template and Third-Party Rights

The project originated from the [KA-Launchly startup template](https://github.com/Kod-Atolye/ka-launchly-startup-template) by Kod Atölye and has been adapted for Sprey.

The original repository does not declare a GitHub license or include a `LICENSE` file. Review the original author's terms and obtain clarification where necessary before redistributing template-derived materials.

Third-party libraries, fonts, images, and services may be subject to their own terms.

## Links

- [Sprey Promo](https://www.sprey.win/)
- [Sprey Processing](https://pay.sprey.win/)
- [Sprey Registration](https://pay.sprey.win/register)
- [Sprey Documentation](https://docs.sprey.win/)
- [Sprey Store](https://sprey.win/store)
- [GitHub Repository](https://github.com/spreywin/sprey-promo)
