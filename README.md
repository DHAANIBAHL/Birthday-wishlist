# 🎂 Dhaani's Birthday Wishlist

A simple website listing the things I'd love for my birthday, so friends and family can pick a gift without guessing.

🔗 **Live site:** https://dhaanibahl.github.io/Birthday-wishlist/

## About

My birthday is on **2 Dec**, and my friends will wonder what I might want. This site collects everything in one place. Each item has a photo, a short note, the price, and a link to the shop where I found it.

## Features

- Wishlist items shown as gift tags with a photo, name, note, price, and the shop's name
- Click any tag to open the product on the shop's website (Meesho, MARS Cosmetics, Silverfied, LOVETC, Trigaine)
- Filter by price range and shop, and sort by price
- Live countdown to my birthday
- A welcome note that pops up when the site opens
- Purple theme with a dark mode that follows your device setting
- Responsive layout that works on phones, tablets, and desktops

## Built With

- HTML, CSS, and plain JavaScript (no frameworks, nothing to install)
- Fonts from [Google Fonts](https://fonts.google.com/): Shrikhand, DM Sans, and DM Mono

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/DHAANIBAHL/Birthday-wishlist.git
   ```
2. Open the project folder:
   ```bash
   cd Birthday-wishlist
   ```
3. Open `index.html` in your browser.

   Or run a small local server and visit http://localhost:5500:
   ```bash
   python -m http.server 5500
   ```

## Adding or Editing Wishlist Items

All items live in the `WISHLIST` list at the top of `script.js`. Add a new entry like this:

```js
{ name: "Example Item", note: "Any colour works.", store: "Meesho", price: 299, link: "https://example.com/item", image: "images/example.jpg" },
```

- `name`: the product name shown on the tag
- `note`: optional short note, like a shade or size
- `store`: the shop's name; it's added to the Shop filter automatically
- `price`: in rupees, just the number
- `link`: the product page on the shop's website
- `image`: optional; a photo in the `images` folder, or a full image URL from the shop

The welcome note is in `index.html`, and the birthday date for the countdown is near the bottom of `script.js` (`BIRTHDAY_MONTH` and `BIRTHDAY_DAY`).

## Project Structure

```
├── index.html    page layout, welcome note, countdown, filters
├── style.css     colours, gift-tag design, dark mode
├── script.js     wishlist items, filters, countdown
└── images/       product photos saved with the site
```

## For Gift-Givers

- Click an item to open the store page.
- Tell me so I know it's taken.
- Handmade gifts, notes, and your presence are just as welcome as anything on this list.

## Privacy

This site doesn't collect personal data.

Thank you for making my birthday special! 🎁
