Linework — Free Bootstrap 5 Illustrator Portfolio Website Template by uiCookies
https://uicookies.com/

Linework is a free portfolio template for illustrators and graphic artists, built on
Bootstrap 5. It is set up for a fictional studio, Theo Park Studio, that draws editorial
illustration, book covers, characters and murals. The look is bold and graphic: an
off-white paper background, three spot inks (tomato, cobalt and sunflower), thick
outlines, hard shadows, Bricolage Grotesque headings and DM Sans body text.

Nearly all of the artwork is inline SVG drawn in one consistent style, with flat
fills printed slightly off-register and a grain overlay. Each illustration can switch
into a blue-pencil sketch version, which the process strip and the case studies use to
show how a commission develops. The home page has the illustrated hero, selected
projects, client wordmarks, services with starting prices, a brief-sketches-final
process strip, a studio section and a testimonial. The projects page filters nine
projects by discipline and opens each one as a case-study dialog with the final art,
a rough and an in-use mock-up. The commissions page has a three-month availability
calendar, a brief form with reference uploads, a shop strip and an FAQ.

Everything runs on vanilla JavaScript with no jQuery. Content stays visible without
JavaScript (case studies then open as page anchors), and animations respect
prefers-reduced-motion.
Free for personal and commercial use. Attribution is optional but always welcome — https://uicookies.com/license/

WHAT'S INSIDE
  index.html            Home page: hero, selected projects, clients, services,
                        process, studio, testimonial
  projects.html         Filterable project grid with nine case-study dialogs
  commissions.html      Availability calendar, brief form, shop strip, FAQ
  css/vendor/           Bootstrap 5.3.8 (minified, self-hosted)
  css/style.css         Template design layer (palette, type, components, artwork)
  js/vendor/            Bootstrap 5.3.8 bundle (includes Popper)
  js/main.js            Template behaviour — vanilla JavaScript, no jQuery
  img/                  Three public-domain images for the studio wall
  CREDITS.txt           Source and licence for each image

NOTES
  - Built on Bootstrap 5. No jQuery, no plugin dependencies.
  - Colours, fonts and the outline weight are custom properties at the top of
    css/style.css. The SVG artwork reads the same colour tokens, so changing
    --tomato, --cobalt or --sun recolours every illustration.
  - The artwork lives as <symbol> elements in the hidden sprite at the top of each
    page and is placed with <use href="#art-...">. Add your own drawing as a new
    symbol, or swap any artwork block for an <img> of your own work.
  - Adding class="sketch" to an artwork SVG shows its blue-pencil version.
  - The calendar builds the current month and the next two from the data-booked and
    data-hold attributes on commissions.html ("month offset:day ranges", for example
    0:1-9,15-21 means days 1-9 and 15-21 of this month are booked).
  - Link to a filtered project list with projects.html?d=murals, straight to a case
    study with projects.html#case-tide-lines, and prefill the brief form with
    commissions.html?type=book-cover.
  - Forms are front-end only: they validate in the browser and show a confirmation,
    and reference files stay on the visitor's device. Point the forms at your
    backend or a form service to make them live.
  - The shop bag is a demo counter; connect the buttons to your shop to sell.
