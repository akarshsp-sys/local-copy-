# Product Detail Page (PDP) — User Journey Document

This document defines comprehensive user journeys for the Product Detail Page (PDP). Each journey captures how a user arrives at the page, interacts with it, and ultimately adds a product to their cart.

---

## Journey 1: Direct Search → Product Selection → Add to Cart

| Field | Details |
|---|---|
| **Title** | Direct Search to Add to Cart |
| **Description** | A user searches for a specific product by name or keyword from the home/search page, lands on the PDP, reviews product details, and adds the item to their cart. |
| **Entry Point** | Site-wide search bar (header) on any page |
| **Preconditions** | - User has access to the website (logged in or guest) <br>- Product is available and in stock <br>- Search index contains the product |

**Steps:**
1. User types a product name or keyword into the search bar.
2. User submits the search query (presses Enter or clicks the search icon).
3. Search results page displays matching products.
4. User scans results and clicks on the desired product thumbnail or title.
5. Browser navigates to the PDP for that product.
6. User reviews product images, title, price, description, and specifications.
7. User selects required product options (e.g., size, colour, quantity).
8. User clicks the **"Add to Cart"** button.

**Outcome:** Product is added to the user's cart. A cart confirmation toast/modal is displayed, and the cart icon updates to reflect the new item count.

---

## Journey 2: Category/Browse Navigation → Product Selection → Add to Cart

| Field | Details |
|---|---|
| **Title** | Browse Category to Add to Cart |
| **Description** | A user navigates through category or sub-category pages (without a specific product in mind), discovers a product, opens its PDP, and adds it to the cart. |
| **Entry Point** | Top navigation menu → Category or Sub-category page |
| **Preconditions** | - User is on the website <br>- Product exists within the selected category <br>- Product is in stock |

**Steps:**
1. User hovers over or clicks a category link in the top navigation bar.
2. User selects a category or sub-category from the dropdown/menu.
3. Category listing page loads with product grid/list.
4. User applies optional filters (price range, brand, rating) or sorts the results.
5. User clicks on a product card that catches their interest.
6. PDP loads for the selected product.
7. User reviews all product information: images (gallery), title, price, ratings, description, and specifications.
8. User selects any mandatory product variants (size, colour, material, etc.).
9. User adjusts quantity if needed.
10. User clicks the **"Add to Cart"** button.

**Outcome:** Product (with selected variants and quantity) is added to the cart. Cart count updates in the header, and a success notification is shown.

---

## Journey 3: External Link / Marketing Campaign → PDP → Add to Cart

| Field | Details |
|---|---|
| **Title** | Marketing Campaign Deep-Link to Add to Cart |
| **Description** | A user arrives at the PDP directly from an external marketing channel (email campaign, social media ad, influencer link, etc.) and adds the featured product to their cart. |
| **Entry Point** | External URL deep-link (email, social media, paid advertisement, QR code) |
| **Preconditions** | - User clicks a valid, non-expired product link <br>- Product is still active and in stock <br>- Page loads successfully |

**Steps:**
1. User clicks a product link in an email newsletter, social media post, or advertisement.
2. Browser opens and navigates directly to the PDP for the promoted product.
3. PDP renders with product images, promotional price/offer details, and description.
4. User reads the product description and reviews promotional offer (discount badge, limited-time tag).
5. User checks product images using the image gallery.
6. User selects required product options (variant, size, colour).
7. User optionally reads reviews or FAQs on the PDP.
8. User clicks the **"Add to Cart"** button.

**Outcome:** Product is added to the cart. If a promotional code is pre-applied via the URL parameter, the discount is reflected in the cart. Cart confirmation is displayed.

---

## Journey 4: Returning User via Browser History / Bookmarks → PDP → Add to Cart

| Field | Details |
|---|---|
| **Title** | Returning User Re-visits PDP to Purchase |
| **Description** | A user who previously viewed a product returns to the PDP (via browser history, bookmark, or recently viewed section) to complete the purchase by adding the product to the cart. |
| **Entry Point** | Browser bookmark, browser history, or "Recently Viewed" section on the homepage/PDP |
| **Preconditions** | - User previously visited the PDP <br>- Product is still available and in stock <br>- The product URL or bookmark is still valid |

**Steps:**
1. User opens the browser and navigates to the bookmarked product URL, or clicks the product from the "Recently Viewed" widget.
2. PDP loads for the previously viewed product.
3. User verifies the product details and confirms the price has not changed (or reviews any price change).
4. User checks if the product is still in stock.
5. User selects product variants (if not pre-selected from last visit).
6. User reviews any new customer reviews added since last visit.
7. User clicks the **"Add to Cart"** button.

**Outcome:** Product is successfully added to the cart. User can proceed to checkout or continue shopping.

---

## Journey 5: Product Recommendations / Upsell → PDP → Add to Cart

| Field | Details |
|---|---|
| **Title** | Recommendation-Driven Product Discovery to Add to Cart |
| **Description** | While viewing one PDP, a user is attracted by a recommended, related, or "frequently bought together" product and navigates to that product's PDP to add it to the cart. |
| **Entry Point** | "Related Products", "You May Also Like", or "Frequently Bought Together" section on an existing PDP |
| **Preconditions** | - User is currently on a PDP <br>- Recommendation engine has loaded related products <br>- Recommended product is in stock |

**Steps:**
1. User is on a PDP for Product A and scrolls down to see the recommendations section.
2. User notices a recommended Product B that complements their current selection.
3. User clicks on the recommended product card.
4. PDP for Product B loads.
5. User reviews Product B's images, price, description, and ratings.
6. User compares Product B with their original selection if needed (opens Product A in a new tab or uses back navigation).
7. User selects variants for Product B.
8. User clicks the **"Add to Cart"** button for Product B.

**Outcome:** Product B is added to the cart alongside (or instead of) Product A. Cart reflects all added items.

---

## Journey 6: Wishlist / Saved Items → PDP → Add to Cart

| Field | Details |
|---|---|
| **Title** | Wishlist to Cart Conversion |
| **Description** | A user revisits a product they previously saved to their Wishlist or "Saved for Later" list, opens its PDP to confirm details, and moves it to the cart. |
| **Entry Point** | User's Wishlist or "Saved Items" page (accessible from account menu or header icon) |
| **Preconditions** | - User is logged into their account <br>- Product was previously added to the wishlist <br>- Product is still available and in stock |

**Steps:**
1. User logs in (if not already) and navigates to their Wishlist/Saved Items page.
2. User scans their saved items and selects a product they want to buy now.
3. User clicks the product name/image to open the full PDP.
4. PDP loads; user reviews the latest price, stock availability, and product information.
5. User selects any required variants not previously chosen.
6. User adjusts quantity if needed.
7. User clicks the **"Add to Cart"** button.
   - Alternatively, user clicks **"Move to Cart"** if that option exists directly on the Wishlist page.

**Outcome:** Product is added to the cart. Optionally, the item may be removed from the Wishlist upon being added to the cart (depending on site logic). Cart count updates.

---

## Journey 7: Shared Product Link → PDP → Add to Cart

| Field | Details |
|---|---|
| **Title** | Peer-Shared Link to Add to Cart |
| **Description** | A user receives a product link shared by a friend or family member (via messaging app, email, or social media), opens it, views the PDP, and adds the product to the cart. |
| **Entry Point** | Shared URL received via WhatsApp, SMS, email, or social media message |
| **Preconditions** | - Shared link is valid and the product is still active <br>- Product is in stock <br>- User can access the website (guest or logged in) |

**Steps:**
1. User receives a product link from a friend/family member.
2. User taps or clicks the shared URL.
3. Browser (or in-app browser) opens the PDP for the shared product.
4. User reviews product images, price, description, and reviews.
5. User checks ratings and reads top customer reviews to validate the recommendation.
6. User selects required product variants (size, colour, quantity).
7. User clicks the **"Add to Cart"** button.

**Outcome:** Product is added to the cart. User can choose to continue shopping or proceed to checkout. They may also share the link further or create an account to track the order.

---

## Journey 8: Out-of-Stock Product → Notify Me → Restock → Add to Cart

| Field | Details |
|---|---|
| **Title** | Back-in-Stock Notification to Add to Cart |
| **Description** | A user visits a PDP for an out-of-stock product, opts into a back-in-stock notification, and returns to add the product to the cart once it becomes available again. |
| **Entry Point** | PDP for an out-of-stock product (via search, category, recommendation, or direct link) |
| **Preconditions** | - Product is currently out of stock on initial visit <br>- "Notify Me" / back-in-stock feature is enabled <br>- Product is restocked before notification expires |

**Steps:**
1. User lands on the PDP for a product that is out of stock.
2. PDP displays an "Out of Stock" or "Currently Unavailable" message; the "Add to Cart" button is disabled or replaced by a **"Notify Me"** button.
3. User clicks the **"Notify Me"** button.
4. User enters their email address (or confirms if logged in) and submits the notification request.
5. System sends a confirmation that the user will be notified when the product is back in stock.
6. Product is restocked; system sends an email/push notification to the user.
7. User clicks the notification link and returns to the PDP.
8. PDP now shows the product as "In Stock" with the **"Add to Cart"** button enabled.
9. User selects desired variants and quantity.
10. User clicks the **"Add to Cart"** button.

**Outcome:** Product is successfully added to the cart. User can proceed to checkout before the item sells out again.

---

## Journey 9: Coupon / Promo Code Application on PDP → Add to Cart

| Field | Details |
|---|---|
| **Title** | Promo Code Validation on PDP → Add to Cart |
| **Description** | A user arrives at the PDP with a coupon or promo code, verifies that the discount applies to the product, and adds it to the cart with the discount reflected. |
| **Entry Point** | PDP accessed via any channel; user has a coupon/promo code |
| **Preconditions** | - User has a valid coupon or promo code <br>- The product is eligible for the discount <br>- Product is in stock |

**Steps:**
1. User arrives at the PDP (via search, campaign link, or category).
2. User reviews product price and checks if a discount/offer badge is already displayed.
3. If not pre-applied, user looks for a promo code input field on the PDP or notes to apply it at checkout.
4. User confirms the effective price after discount (if PDP supports inline code entry) or notes to apply at checkout.
5. User selects product variants and quantity.
6. User clicks the **"Add to Cart"** button.
7. If promo code is applied at the cart/checkout level, user navigates to the cart and enters the code in the promo code field.

**Outcome:** Product is added to the cart. The promotional discount is applied (either on PDP or at cart/checkout), and the discounted price is visible in the cart summary.

---

## Journey 10: Mobile User → PDP → Add to Cart

| Field | Details |
|---|---|
| **Title** | Mobile Browsing to Add to Cart |
| **Description** | A user on a mobile device browses, finds a product, and uses the mobile-optimised PDP to add the product to the cart using touch interactions. |
| **Entry Point** | Mobile browser or native app — via search, category, or external link |
| **Preconditions** | - User is on a mobile device (smartphone or tablet) <br>- Website is responsive / mobile-optimised <br>- Product is in stock |

**Steps:**
1. User opens the mobile browser or app and navigates to the website.
2. User searches for a product or taps a category from the mobile navigation menu (hamburger menu).
3. User scrolls through product listings and taps on a product card.
4. Mobile-optimised PDP loads with swipeable image gallery and vertically stacked layout.
5. User swipes through product images.
6. User scrolls down to read the product title, price, description, and customer reviews.
7. User taps on variant selectors (size, colour) to choose options.
8. User adjusts quantity using the +/- stepper.
9. User taps the **"Add to Cart"** button (typically a prominent sticky CTA at the bottom of the screen).

**Outcome:** Product is added to the cart. Cart icon in the mobile header updates with item count. A confirmation banner or bottom sheet appears, giving the user options to view the cart or continue shopping.

---

## Summary Table

| # | Journey Title | Entry Point | Key Interaction | Outcome |
|---|---|---|---|---|
| 1 | Direct Search → Add to Cart | Search bar | Search → Results → PDP | Product added to cart |
| 2 | Browse Category → Add to Cart | Top navigation | Category page → PDP | Product added to cart |
| 3 | Marketing Campaign → Add to Cart | External deep-link | Direct PDP load | Product added to cart (with promo) |
| 4 | Returning User (Bookmark) → Add to Cart | Browser bookmark / Recently Viewed | Direct PDP load | Product added to cart |
| 5 | Recommendations → Add to Cart | PDP recommendations widget | Recommended PDP | Product added to cart |
| 6 | Wishlist → Add to Cart | Wishlist/Saved Items page | Wishlist → PDP | Product added to cart |
| 7 | Shared Link → Add to Cart | Shared URL (chat/social) | Direct PDP load | Product added to cart |
| 8 | Out-of-Stock → Notify Me → Add to Cart | Out-of-stock PDP | Notify Me → Restock email → PDP | Product added to cart |
| 9 | Promo Code → Add to Cart | Any entry + coupon code | PDP + promo code | Product added to cart with discount |
| 10 | Mobile User → Add to Cart | Mobile browser/app | Swipe gallery → Sticky CTA | Product added to cart |
