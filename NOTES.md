# Mistvale Tea Co. - Notes

## Implementation Summary

The one-page Mistvale Tea Co. store was improved using HTML, CSS and vanilla JavaScript.

The implementation includes:

- Responsive product grid
- Product search
- Category filtering
- Product sorting
- Shopping cart
- Quantity controls
- Stock validation
- Sold-out handling
- WELCOME10 coupon
- Shipping calculation
- Delivery pincode checker
- Product quick view
- FAQ section
- Newsletter interface
- Responsive mobile layout
- Accessibility improvements
- SEO and structured data

## Business Rules

Product prices are calculated from the supplied PRODUCTS data.

A customer can add a maximum of 5 units of a product and the quantity can never exceed available stock.

Sold-out products cannot be added to the cart and remain last when products are sorted.

WELCOME10 is case-insensitive and provides 10% off eligible items when the subtotal is at least ₹399.

Products in the Gifts category are excluded from the WELCOME10 discount.

The maximum WELCOME10 discount is ₹150.

Shipping is calculated using the amount after discount.

The final total is rounded to the nearest rupee.

Currency values use Indian Rupee formatting.

Search, category filtering and sorting work together.

Delivery availability is checked using the supplied API.checkPincode() function.

## Images

Eight product images were created for the supplied products and stored as:

- p101.png
- p102.png
- p103.png
- p104.png
- p105.png
- p106.png
- p107.png
- p108.png

A separate hero-banner.png image is used for the homepage hero section.

## Accessibility

The implementation includes semantic HTML, keyboard focus states, form labels, descriptive image alt text, ARIA status messages and reduced-motion support.

## Responsive Design

The page was designed to work from a 360px mobile viewport through desktop screen sizes without horizontal scrolling.

## Newsletter

No newsletter backend or mailing service was supplied.

The newsletter form therefore performs client-side validation only and does not pretend that a real subscription has been created.

## Development Decision

Where functionality was not provided by the starter files, the implementation uses a temporary frontend-only solution without inventing unsupported backend behaviour.