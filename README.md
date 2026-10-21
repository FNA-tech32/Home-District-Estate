# Home District Estate

Home District Estate is a multi-page real estate website for browsing listings, meeting agents, reading property articles, and getting in touch with the team.

The site is a static frontend. Open `index.html` in a browser to view it. There is no build step required for the compiled styles in `sass/main.css`.

## Pages

| Page | File | What it covers |
| --- | --- | --- |
| Home | `index.html` | Hero, featured properties, areas, agents, blog highlights, and calls to action |
| Listings | `property.html` | Property catalog |
| Property details | `propert-details.html` | A single listing with description and location |
| About | `about.html` | Company story, mission, and team |
| Agents | `agents.html` | Agent profiles |
| Blog | `blog.html` | Property and buying articles |
| Blog details | `blog-detailes.html` | A single article |
| Shop | `shop.html` | Services and products |
| Cart | `cart.html` | Selected items |
| Checkout | `checkout.html` | Checkout form |
| Contact | `contactus.html` | Enquiry form and office details |
| Sign up | `signup.html` | Account registration form |
| Sign in | `signin.html` | Account sign-in form |
| Forgot password | `forget-password.html` | Password reset form |

Navigation on every page links Home, Listing, Contact, Agents, About, Blog, and Shop. Sign up and the cart are available from the header.

## Contact

These details appear in the footer on every page and on the contact page:

- **Address:** 42 Harbour View Road, District Centre, Melbourne VIC 3000, Australia
- **Phone:** (03) 9876 2140
- **Email:** hello@homedistrictestate.com

## Technologies

- HTML5
- CSS3
- Sass (source in `sass/`, compiled output in `sass/main.css`)
- JavaScript (`assets/js/navbar.js` for the menu, `assets/js/script.js` for page behaviour)
- Google Fonts (Lato)

## Project structure

```text
Home-District-Estate/
├── assets/
│   ├── img/
│   └── js/
├── sass/
├── index.html
├── about.html
├── agents.html
├── blog.html
├── blog-detailes.html
├── property.html
├── propert-details.html
├── shop.html
├── cart.html
├── checkout.html
├── contactus.html
├── signin.html
├── signup.html
├── forget-password.html
└── README.md
```

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server so relative links and assets load the same way they would on a host.

```bash
# example with Python
python -m http.server 5500
```

Then visit `http://localhost:5500`.

## Notes

Forms, cart totals, and account actions are frontend-only. They do not send data to a server or store accounts. Property, agent, and blog content is written directly in the HTML pages.
