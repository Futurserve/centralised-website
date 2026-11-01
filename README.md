# centralised-website

The Centralised Business Solutions website (centralised.co.za), built with Jekyll and hosted free on GitHub Pages.

## Reusing this as a template for another site

Everything business-specific lives in a few places:

1. `_config.yml`: name, tagline, description, web address, brand colours and fonts, contact details, booking link, company and regulatory footer.
2. `assets/img/`: logo files (normal and reversed), favicon, social share image, contact photo.
3. `_data/navigation.yml`: the menu.
4. The page files (`index.html`, `services.html`, `partner.html`, `about.html`): the wording.

Layout, header, footer and styles (`_layouts/`, `_includes/`, `assets/css/site.css`) are shared and normally don't need changing. Colours and fonts in the stylesheet are read from `_config.yml`.

## Booking button

Set `contact.booking_url` in `_config.yml` to the Google Calendar appointment schedule link. While it's blank, every "Book a call" button goes to the contact section.

## Custom domain

Add a `CNAME` file containing `centralised.co.za` only when the domain's DNS is pointed at GitHub Pages.
