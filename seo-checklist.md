# SEO Checklist for Product Pages

How to optimize your product pages for search engines.

## On-Page Essentials

### Title Tag
- [ ] Include primary keyword
- [ ] Keep under 60 characters
- [ ] Add brand name at end
- [ ] Make it compelling to click

**Format**: `[Product Name] - [Key Benefit] | [Brand]`

**Example**: `Wireless Bluetooth Headphones - 40hr Battery | AudioPro`

### Meta Description
- [ ] Include primary keyword naturally
- [ ] Keep between 120-155 characters
- [ ] Include call to action
- [ ] Mention unique selling point

### URL Structure
- [ ] Short and readable
- [ ] Include main keyword
- [ ] Use hyphens between words
- [ ] Avoid parameters when possible

**Good**: `/wireless-headphones-pro`

**Bad**: `/product.php?id=12847&cat=3`

## Product Descriptions

- [ ] Minimum 300 words for main products
- [ ] Unique content (not manufacturer copy)
- [ ] Include primary keyword in first 100 words
- [ ] Use related keywords naturally
- [ ] Break up with subheadings
- [ ] Include specifications in HTML (not just images)

## Images

- [ ] Descriptive file names (`blue-wireless-headphones.jpg`)
- [ ] Alt text with keywords
- [ ] Compressed for fast loading
- [ ] Multiple angles provided
- [ ] WebP format where possible

## Schema Markup

Add structured data for rich results:

```json
{
  "@context": "https://schema.org",
  "@type": "Product",
  "name": "Product Name",
  "image": "image-url.jpg",
  "description": "Product description",
  "brand": {
    "@type": "Brand",
    "name": "Brand Name"
  },
  "offers": {
    "@type": "Offer",
    "price": "29.99",
    "priceCurrency": "GBP",
    "availability": "https://schema.org/InStock"
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.5",
    "reviewCount": "24"
  }
}
```

## Internal Linking

- [ ] Link to related products
- [ ] Link to relevant category pages
- [ ] Use descriptive anchor text
- [ ] Add breadcrumb navigation

## Page Speed

- [ ] Images optimized
- [ ] Lazy loading enabled
- [ ] Minimal JavaScript
- [ ] Core Web Vitals passing
