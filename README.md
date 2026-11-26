# Shofuku Japanese Restaurant Website

**A multi-page website for a Japanese restaurant, with a live order builder that calculates the bill as you go and a feedback form with emoji ratings.**

![Shofuku Video](media/Shofuku_Video.mp4)

🔗 [Live Demo](https://melonmuse.github.io/Restaurant_Website/)


## Overview
Many small restaurants rely only on social media, so customers can't easily find the menu, see prices, order, or leave feedback. This CSC307 project is a website concept for Shofuku, a Japanese restaurant, that brings its story, menu, gallery, ordering, and contact details together on one site.

*This is a university course project and is not the restaurant's official website.*

## Highlights
- **Six pages:** Home (with an intro video), Menu, Order, Gallery, Contact, and About, sharing the same navigation bar and footer.
- **Dynamic order form:** a new item row appears once the previous row is filled in.
- **Live bill calculation:** the total updates every time an item or quantity changes.
- **Order validation:** the order can't be submitted if any row has an item without a quantity (or the other way round).
- **Feedback form** with an emoji rating that must be selected before submitting.

## Skills Demonstrated
- Building a multi-page site with a shared stylesheet plus one stylesheet per page
- Handling DOM events (adding form rows, recalculating totals as the user changes the order)
- Validating forms on the client side and resetting the form after submission
- Embedding media and building a gallery layout

## Tech Stack
HTML · CSS · JavaScript · GitHub Pages

## Getting Started
No installation needed. Open the **[live demo](https://melonmuse.github.io/Restaurant_Website/)** in an up-to-date browser.

To run it locally, clone the repository and open `index.html`:
```bash
git clone https://github.com/melonmuse/Restaurant_Website.git
```

## Testing
- [ ] Fill in an order row and check that a new row appears.
- [ ] Order 2 Gyoza and 1 Okonomiyaki. The total should be 460.
- [ ] Submit a row with an item but no quantity. You should see an alert.
- [ ] Submit feedback without an emoji rating. You should see an alert.

## Team
- **Abeer Abu Shiekah**
- **[Team member 2]**
