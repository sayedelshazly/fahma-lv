# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary users are mobile-first Egyptian foodies and burger enthusiasts seeking quick, high-quality meal orders with zero friction. They order lunch, dinner, or late-night meals directly from their smartphones and prefer fast, immediate WhatsApp checkout over complex registration forms or third-party aggregator apps.

## Product Purpose

Fahma (فحمة برجر كلوب) delivers an appetizing, high-energy digital storefront for charcoal-grilled gourmet burgers in Cairo, Egypt. It converts visitors into repeat diners by providing a mouth-watering visual menu, interactive cart customization, instant WhatsApp order routing, and clear order status tracking.

## Positioning

Authentic charcoal-grilled burgers ("مشوي على الفحم") and smash burgers with real smoky flavor, bespoke sauces, and a distinctive "Golden VIP" tier, combined with an effortless WhatsApp ordering flow that bypasses platform fees and customer account friction.

## Operating Context

- Region & Currency: Cairo, Egypt; Egyptian Pounds (ج.م / EGP).
- Operating Hours: Daily from 12:00 PM to 2:00 AM.
- Primary Interaction Environment: Mobile web browsers (RTL Arabic) with tactile touch navigation, slide-over cart drawers, and WhatsApp handoff.

## Capabilities and Constraints

- Capabilities:
  - Interactive menu with real-time search, category filtering (beef, chicken, gold, sides, drinks), and sorting (popular, new, price).
  - Slide-over shopping cart with subtotal calculation, fixed delivery fee, and order counter.
  - Itemized WhatsApp order message generation with recipient routing.
  - Order tracking lookup interface with milestone progress visualization.
- Constraints:
  - Fully client-side architecture without backend customer authentication or persistent database dependencies.
  - Native RTL Arabic layout requirement (`dir="rtl"`, `lang="ar"`).
  - High performance and smooth responsiveness on mobile networks.

## Brand Commitments

- Brand Name: فحمة / فحمة برجر كلوب (Fahma Burger Club).
- Tagline & Identity: "أصل البرجر" / "قطمة واحدة وتدخل المود" / "مش مجرد برجر… دا قصة".
- Visual & Tonal Signature: Smoky, flame-inspired energy (deep charcoal tones, ember orange `#ff8a4c`/`#e8481a`, luxury gold accents for VIP items). Warm, street-smart Egyptian colloquial Arabic tone.

## Evidence on Hand

- Functional web application codebase: `index.html`, `style.css`, and `main.js`.
- Curated catalog of products with prices, tags, preparation times, ingredient breakdowns, and photography.
- Custom canvas ember particle animation and GSAP/ScrollTrigger choreography.

## Product Principles

1. Zero-Friction Ordering: Eliminate all hurdles between appetite and checkout; no mandatory account registration or bloated multi-step checkout.
2. Sensory Appetite Appeal: Visuals, typography, and micro-interactions reinforce the sizzle, smoke, and freshness of charcoal grilling.
3. Authentic Local Voice: Communicate warmly and directly using Egyptian colloquial Arabic with authentic culinary pride.
4. Mobile-First Ergonomics: Optimize for one-handed thumb interaction, instant sheet modals, and rapid tactile feedback.

## Accessibility & Inclusion

- Native RTL semantic HTML with dedicated ARIA attributes on modals, cart triggers, and search inputs.
- Dedicated `prefers-reduced-motion` support across the preloader, canvas embers, and GSAP timeline animations.
- Accessible font scaling and readable contrast over dark theme backgrounds.

