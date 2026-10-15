# 🎂 Dhaani's Birthday Wishlist

A simple website listing the things I'd love for my birthday, so friends and family can pick a gift without guessing.

🔗 **Live site:** [https://your-link-here]

## About

My birthday is on **2 Dec**, and my friends will wonder what I might want. This site collects everything in one place. Each item has a photo, a short note, an approximate price, and a link to buy it.

## Features

- Wishlist items shown as cards with image, name, price, and a buy link
- Countdown to my birthday
- Responsive layout that works on phones, tablets, and desktops

## Built With

- [HTML, CSS, JavaScript]
- 
## Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/[your-username]/[repo-name].git
```
2. Open the project folder:
```bash
   cd [repo-name]
```
3. Open `index.html` in your browser.
   If you're using Node:
```bash
   npm install
   npm start
```

## Adding or Editing Wishlist Items

All items live in `[wishlist.json / data.js]`. Add a new entry like this:

```json
{
  "name": "Example Item",
  "price": "$50",
  "category": "Books",
  "priority": "Top pick",
  "image": "images/example.jpg",
  "link": "https://example.com/item",
  "claimed": false
}
```

Set `"claimed": true` once someone has taken it.

## Project Structure

```
├── index.html
├── style.css
├── script.js
├── wishlist.json
└── images/
```

## For Gift-Givers

- Click an item to open the store page.
- Tell me so I know it's taken.
- Handmade gifts, notes, and your presence are just as welcome as anything on this list.

## Privacy

This site doesn't collect personal data. 

Thank you for making my birthday special! 🎁
