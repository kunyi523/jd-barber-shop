# JD Barber Shop — unofficial Hamilton pitch sample

A mobile-first one-page website **proposal** for **JD Barber Shop** (also listed as J.D. Barber Shop / JD Barbershop) at 6 Ottawa St N, Hamilton, ON L8H 3Y7.

**This is not the shop’s official website.** It is an unofficial sample prepared as a pitch so the owner can see what a simple site could look like. It is not affiliated with JD Barber Shop.

There is no online booking and no online payment on this page. The Ottawa Street BIA listing says walk-ins are accepted, or call **289-684-5758** to make an appointment. This page only helps people **call** or **get directions**.

No official Instagram or Facebook page was found. Do not treat [jdbarbers.ca](https://www.jdbarbers.ca/) as this shop — that is a different Toronto shop on Queen Street West.

Live URL (after Pages is on): [https://kunyi523.github.io/jd-barber-shop/](https://kunyi523.github.io/jd-barber-shop/)

## How to open

The whole site is one self-contained file: `index.html` (CSS is inlined). Open that file in a browser, or visit the Pages URL on a phone.

Optional local server, from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## GitHub Pages

Static files live at the **repository root**. Enable branch-based Pages (same pattern as the Gus & Son sample):

1. **Settings → Pages**
2. Build and deployment → Source: **Deploy from a branch**
3. Branch: **main**, folder: **/** (root)
4. Save

GitHub will serve the site at `https://kunyi523.github.io/jd-barber-shop/`.

Do not add a GitHub Actions workflow for Pages. This account cannot write workflow files, and the owner will use branch-based Pages.

## What’s on the page

- Shop name, Ottawa Street North address, click-to-call (`tel:+12896845758`)
- Thumb-sized **Call** and **Directions** buttons
- Hours from the [Ottawa Street BIA listing](https://shopottawastreet.com/directory/listing/jd-barber-shop/): Tuesday–Saturday 9:00 am–4:00 pm; closed Sunday and Monday
- Licensed Unsplash atmosphere photo — **not** a photo of this shop
- George’s career path from the BIA profile, paraphrased without turning relative phrases into calendar years
- Real customer quotes from public listings (Google via Birdeye, and older canada247 directory reviews). Names are as they appeared. Unnamed directory reviews are labelled “Public review.”
- About 4.8 from public listings (~54 Google reviews on Birdeye) — not a live scrape
- Google Map embed and Get directions
- A discreet footer stating this is an unofficial sample

Built as a simple HTML one-pager (a small script only highlights today’s hours in the America/Toronto timezone).

## Hours note

The BIA listing is treated as the source of truth. canada247 and BestProsInTown repeat the same Tuesday–Saturday 9:00 am–4:00 pm hours.

A Birdeye listing shows Monday–Friday 9:00 am–6:00 pm and Saturday closed. Those hours conflict with the BIA listing and were **not** used.

This page does not claim a confirmed cash-only policy. One recent public review said they were told it was cash only; that is all we know.

## What this page does not do

- Invent prices, a service menu, or amenities
- Pretend stock photos are the shop
- Link to a Toronto shop or invent social accounts
- Take bookings or payments
