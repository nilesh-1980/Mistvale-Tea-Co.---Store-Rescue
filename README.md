# Mistvale Tea Co. – Store Rescue

A responsive one-page ecommerce storefront for Mistvale Tea Co., built as part of the developer assessment.

The project uses HTML, CSS and vanilla JavaScript with no frontend frameworks or libraries.

## Features

- Responsive one-page tea store
- Product search
- Category filtering
- Product sorting
- Product quick view
- Shopping cart
- Quantity controls
- Stock validation
- Sold-out product handling
- WELCOME10 coupon support
- Shipping calculation
- Free-shipping progress indicator
- Delivery pincode checker
- FAQ section
- Newsletter interface
- Responsive mobile layout
- Accessible form controls and keyboard focus states
- SEO metadata
- Product, Organization and FAQ structured data

## Business Rules

- Product prices are calculated from the supplied PRODUCTS data.
- Maximum quantity is 5 units per product.
- Quantity can never exceed available stock.
- Sold-out products cannot be added to the cart.
- Sold-out products remain last when sorting.
- WELCOME10 is case-insensitive.
- WELCOME10 requires a minimum subtotal of ₹399.
- WELCOME10 provides 10% off eligible items.
- Gifts are excluded from the coupon discount.
- Coupon discount is capped at ₹150.
- Shipping is ₹49 unless the amount after discount reaches the free-shipping threshold.
- Only the final order total is rounded to the nearest rupee.
- Prices are displayed in INR using Indian number formatting.
- Search, filters and sorting work together.
- Delivery availability is checked using the supplied API.checkPincode() function.

## Project Structure

```text
mistvale-assessment-kit/
├── index.html
├── BRAND.md
├── README.md
├── NOTES.md
├── PROMPTS.md
└── images/
    ├── hero-banner.png
    ├── p101.png
    ├── p102.png
    ├── p103.png
    ├── p104.png
    ├── p105.png
    ├── p106.png
    ├── p107.png
    └── p108.png
