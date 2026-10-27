# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Coffee to Grow – Café in Front Royal, VA
purpose: Home page for Coffee to Grow cafe in Front Royal, Virginia
sections:
- `#hero` — hero introduction and location overview: Front Royal, John Marshall Hwy
- `#offerings` — featured menu items and sample selections: Churro latte, Churro Waffle, Espresso shot, Pour Over Coffee, Gourmet Hot Cocoa, Chocolate Chip Cookie, Soda
- `#faq` "Good to know" — frequently asked questions: Front Royal
- `#contact` — contact details and location information: John Marshall Hwy, Front Royal

## menu.html → /menu
title: Coffee, Tea & Pastry Menu with Prices | Coffee to Grow
purpose: Display the full cafe menu with categories, item descriptions, and prices.
sections:
- `#menu-intro` "Menu" — text and category navigation links: Espresso, Pour Over Coffee, Cold Brew, Hot Chocolate, Italian soda, Homemade Pastries, Soda and Juice, Tea, Breakfast, Blended Drinks
- `#full-list` "Espresso" — priced espresso beverages: Espresso shot, Americano, Latte, Churro latte, Mocha, Cookie Monster
- "Pour Over Coffee" — priced pour over and drip coffee: Pour Over Coffee, House Coffee
- "Cold Brew" — priced cold brew beverages: Crafted Cold Brew
- "Hot Chocolate" — priced hot cocoa beverages: Gourmet Hot Cocoa, Hot cocoa
- "Italian soda" — priced Italian soda beverages: Italian soda
- "Homemade Pastries" — priced baked goods and pastries: Chocolate Chip Cookie, Seasonal Muffin, Seasonal Poptart, Brownie, Banana bread, Scones
- "Soda and Juice" — priced canned or bottled soda: Soda
- "Tea" — priced teas, matcha, and chai drinks: Earl Grey Tea, Hibiscus Tea, English Breakfast Tea, Matcha Latte, Chai Tea, Chai Latte, London Fog
- "Breakfast" — priced breakfast waffles: Vanilla Waffle, Churro Waffle
- "Blended Drinks" — priced blended drinks: Blended drink
- `#menu-close` — phone number, address, and serving hours prompt
also: The menu item names and prices are mirrored between the visible menu and the JSON-LD structured data block.
also: The menu items and categories are rendered in markup directly matching the JSON-LD structured data block.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `llms.txt` — 139 bytes — too small to hold content
- `robots.txt` — 45 bytes — too small to hold content
- `sitemap.xml` — 160 bytes — too small to hold content

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
