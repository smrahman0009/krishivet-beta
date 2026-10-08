# KrishiVet website: beta preview

A single-page static preview of the new KrishiVet Nutra Solution website, for online testing and feedback before the real site is built.

**Live preview:** https://smrahman0009.github.io/krishivet-beta/

## What this is (and is not)

- A **beta preview**, not the official KrishiVet website (that is [krishivet.ca](https://krishivet.ca)).
- **Sample content:** product details, doses, prices, contact numbers and some text are placeholders, marked "Sample" or "To confirm" on the page.
- The **contact form does not send** anything, and the Call / WhatsApp buttons have no number yet.
- Hidden from search engines (`noindex`), so it never competes with krishivet.ca in Google.

## Google Analytics (off until an ID is added)

Analytics and its cookie banner are built in but switched off.
To switch them on:

1. Open `index.html` in this repository and click the pencil icon (Edit).
2. Near the top, find `window.KV_GA_ID = '';`
3. Paste the Measurement ID between the quotes, for example `window.KV_GA_ID = 'G-ABC123XYZ9';`
4. Click **Commit changes**. The site updates in about a minute.

Visitors then see a cookie banner; analytics loads only if they click **Accept**.
Every visit is tagged with the content group "Beta preview".

## Product pages

Each product has its own page inside this single page, for example
`/#/products/calcium-supplement`. The browser's Back button works as usual.

## Photo credits

All photos are free to use. Credit is not required by these licenses, but is given here.

| Photo | Photographer | Source | License |
|---|---|---|---|
| Hero: farmer with oxen, Rangpur | Masudar Rahman | [Pexels](https://www.pexels.com/photo/sunlight-over-farmer-with-oxes-on-field-16559742/) | Pexels License |
| Distributor background: rice fields, Banshkhali | Sharafat Siddiqui | [Unsplash](https://unsplash.com/photos/aerial-view-of-green-grass-field-during-daytime-RfHhohVQLnQ) | Unsplash License |
| Iron Supplement card: cow and calf, Dinajpur | Fareed Akhyear Chowdhury | [Unsplash](https://unsplash.com/photos/N0ouxDAN8Nw) | Unsplash License |
| Calcium Supplement card: calf nursing | Fareed Akhyear Chowdhury | [Unsplash](https://unsplash.com/photos/dFHTJxzs3GU) | Unsplash License |
| Liver Tonic card: young calf, Sonagazi | Tamim Arafat | [Unsplash](https://unsplash.com/photos/G24QRa265Bw) | Unsplash License |
| Appetizer card: young goat, Dhaka | Nidal Adnan Kibria | [Unsplash](https://unsplash.com/photos/BS6cDBU3UfQ) | Unsplash License |

Product photos are placeholders until KrishiVet's real package photos are ready.
The logo and team photos belong to KrishiVet and its team members.

## Source

Built from the reviewed home page mockup for the KrishiVet redesign (see `docs/WEBSITE_BLUEPRINT.md` in the KrishiVet repository, branch `local-dev-setup`).
The production site will be rebuilt in Next.js; this preview is plain HTML, CSS and JavaScript with no build step.
