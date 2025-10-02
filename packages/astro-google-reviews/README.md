# Google Reviews Widget for Astro

Embed the Google reviews widget (powered
by [Wally](https://getwally.net/?utm_source=astro&utm_medium=package&utm_campaign=google)) in your Astro site with a
single component.

## Installation

```sh
npm install astro-google-reviews
```

## Usage

1. **Get your Widget ID:**
    - [Log in to Wally](https://app.getwally.net/?utm_source=astro&utm_medium=package&utm_campaign=google).
    - Import your Google reviews.
    - Customize your widget layout and design.
    - Copy your Widget ID.

2. **Import and use the component in your Astro page:**

```astro
---
import WallyGoogleReviews from 'astro-google-reviews';
---

<WallyGoogleReviews widgetId="YOUR_WIDGET_ID" />
```

- The widget script is automatically injected (only once per page).
- No extra setup or configuration is required.

## Example

```astro
<WallyGoogleReviews widgetId="65740ce811406c0014250535" />
```
