# Tomorrowland Pearls ➜ NIS Converter

A simple, mobile-friendly web app to convert Tomorrowland Pearls to Israeli Shekels (₪), and share real dish prices with the community. Built for festival-goers to budget and discover actual food and drink prices, with upvote/downvote reliability.

## Overview
This site allows users to:
- Instantly convert Pearls (Tomorrowland's festival currency) to NIS using configurable rates.
- Add dishes they purchased (name + Pearls cost) to a community table.
- Vote on the accuracy of dish prices (one vote per user per dish).
- See the most reliable prices float to the top.

## Features
- **Pearl ➜ NIS Converter**: Enter Pearls, adjust rates, and get instant conversion.
- **Community Dish Prices**: Add, view, and vote on real dish prices.
- **Voting System**: Upvote/downvote to surface the most accurate info.
- **Mobile-First Design**: Optimized for use on-site at the festival.
- **Anonymous Auth**: No sign-up required; voting is tracked anonymously.

## Live Demo
[https://galcesana.github.io/pearls-to-nis/](https://galcesana.github.io/pearls-to-nis/)

## Technologies Used
- **HTML, CSS, JavaScript** (Vanilla, no frameworks)
- **Firebase** (Firestore, Auth)
- **Responsive Design**

## How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/galcesana/pearls-to-nis.git
   cd pearls-to-nis
   ```
2. Open `index.html` in your browser.
   - For full functionality (community dishes), you need to set up your own Firebase project and update the Firebase config in `index.html`.
3. (Optional) To deploy, use GitHub Pages or any static hosting provider.

## License
This project is provided as-is, without warranty. Not affiliated with Tomorrowland. See [LICENSE](LICENSE) for details.

