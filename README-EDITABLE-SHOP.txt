HUGS FROM HOME — EDITABLE WEBSITE
================================
This is the existing Hugs From Home design, updated to support changing products and your homepage from an Android phone.

WHAT'S INCLUDED
- index.html: the customer-facing shop (same design, basket and order enquiry form)
- images/: the real product photos from your uploaded pictures
- data/products.json: product catalogue (14 initial products)
- data/site.json: homepage text, featured photos and seasonal promotion
- .pages.yml: settings for a free mobile-friendly editing service, Pages CMS
- admin/index.html: shop-manager link (does not store a login or passwords)
- thanks.html: enquiry form confirmation

IMPORTANT — THIS IS NOT LIVE YET
The shop files are ready, but the editing service is NOT linked to your GitHub or hosting account. These steps are required once:
1. Make a free GitHub account at github.com if you don't already have one.
2. Create a new repository, for example hugs-from-home-shop. It can be private if allowed by your hosting plan.
3. Upload the CONTENTS of this ZIP to the root of that repository. Keep folders and the hidden file .pages.yml.
   On Android, extract the ZIP in My Files first. If uploading a whole directory is awkward on mobile, use GitHub's browser in desktop mode or an existing GitHub integration that can commit the site files.
4. In Netlify, choose Add new project > Import an existing project > GitHub > select this repository.
   Build command: leave empty. Publish directory: root (.). Netlify will deploy this static site on each change.
   IMPORTANT: If you already deployed an earlier Hugs From Home site manually, use the same domain by transferring the domain/hostname or linking the existing Netlify site; do not assume a second Netlify site takes over the old address.
5. Visit https://app.pagescms.org from your phone; sign in with GitHub, install the Pages CMS GitHub App for your repository and open it.
6. You will see: Shop products and Homepage and seasonal banner. Edit an item and save.
7. Pages CMS writes the updated JSON to GitHub. Netlify auto-deploys the change. Refresh the shop to see it.

DAY-TO-DAY
- Add new product: Shop products > add item. Enter a NEW unique product ID with letters/numbers/dashes, a photo, price, category, season, description, and note. Toggle Show on website ON and In stock ON.
- Hide Christmas products: switch Show on website OFF; switch it on again next Christmas.
- Sold out: switch In stock OFF. Shoppers see Sold out and cannot add it to the basket.
- Change homepage: use Homepage and seasonal banner. After Christmas, change photos and promo text, set Seasonal collection name to e.g. Easter (must match product season), or turn off Show seasonal banner.
- Add Easter products: set Season or collection to Easter. Website filters automatically create a new Easter button.
- For painting kits always mention paint colours may vary. There is also a general disclaimer below the product grid.

NOT A PAYMENT CHECKOUT
Basket + order form creates an ENQUIRY only; it does not charge customers.
The form uses Netlify Forms and must be tested after hosting is configured. Check Netlify Forms is enabled and receiving submissions before sharing the shop. Card payments require a separate payment provider integration.

BEFORE ACCEPTING ORDERS
- Verify all product names, prices, contents, shipping charges and available stock.
- Provide your business contact details, shipping and returns policies, privacy notice, and applicable UK consumer information.
- Check toy safety requirements for kids' kits and intellectual property rights for all designs.
- Do not rely on this static site for automatic card payment processing or inventory locking.

No existing shop or payment account has been connected automatically.
