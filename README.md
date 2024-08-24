| Facebook | X / Twitter | LinkedIn | Discord |
| -------- | ----------- | -------- | ------- |
| ![Thumbnail](https://github.com/muhammadhafijur/open-graph-starter/blob/main/images/facebook-thumbnail.png) | ![Thumbnail](https://github.com/muhammadhafijur/open-graph-starter/blob/main/images/twitter-thumbnail.png) | ![Thumbnail](https://github.com/muhammadhafijur/open-graph-starter/blob/main/images/linkedin-thumbnail.png) | ![Thumbnail](https://github.com/muhammadhafijur/open-graph-starter/blob/main/images/discord-thumbnail.png) |


# Open Graph Starter

Welcome to **open-graph-starter**! This project provides a simple template to get started with Open Graph and Twitter meta tags. Easily integrate social media metadata into your web pages to enhance how your content appears when shared on platforms like Facebook, LinkedIn, and Twitter.

## Table of Contents

1. [Usage](#usage)
2. [Meta Tags](#meta-tags)
3. [Open Graph Checker](#open-graph-checker)

## Usage


1. **Copy the Meta Tags:** Include the provided Open Graph and Twitter meta tags in the `<head>` section of your HTML documents.
2. **Customize the Content:** Replace placeholder content with your own titles, descriptions, image URLs, and site names.
3. **Verify Implementation:** Use the tools provided below to check and preview how your meta tags are rendered.

## Meta Tags


```html
<!-- Open Graph Meta Tags -->
<meta property="og:title" content="Discover Events, Jobs, Resources, and More | DevHubBD" />
<meta property="og:description" content="Discover companies, find jobs, explore events, and access resources all in one place on DevHubBD." />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://www.devhubbd.com/" />
<meta property="og:image" content="./images/og.png" />
<meta property="og:image:alt" content="A description of the image" />
<meta property="og:site_name" content="Your Website Name" />

<!-- Twitter Meta Tags -->
<meta name="twitter:title" content="Discover Events, Jobs, Resources, and More | DevHubBD" />
<meta name="twitter:description" content="Discover companies, find jobs, explore events, and access resources all in one place on DevHubBD." />
<meta name="twitter:image" content="./images/og.png" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:url" content="https://www.devhubbd.com/" />

<!-- General Meta Tag -->
<meta name="description" content="Discover companies, find jobs, explore events, and access resources all in one place on DevHubBD." />
```


## Open Graph Checker

Verify and preview how your meta tags appear on social media:

- **[Free Open Graph Checker Chrome Extension](https://chromewebstore.google.com/detail/social-share-preview/ggnikicjfklimmffbkhknndafpdlabib)** (Supports localhost and live sites)



## With OG Tags, Canonical, Schema, Favicon, and Viewport

To optimize your website's SEO and social media sharing, include the following tags in your HTML `<head>` section:

```html
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Page Title</title>

    <!-- Open Graph Meta Tags -->
    <!-- Open Graph meta tags for social media sharing -->
    <meta property="og:title" content="Your Title Here" />
    <meta property="og:description" content="Your Description Here" />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://www.yoursite.com/" />
    <meta property="og:image" content="https://www.yoursite.com/image.jpg" />
    <meta property="og:site_name" content="Your Site Name" />

    <!-- Twitter Card Meta Tags -->
    <!-- Twitter card meta tags for Twitter sharing -->
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:title" content="Your Title Here" />
    <meta name="twitter:description" content="Your Description Here" />
    <meta name="twitter:image" content="https://www.yoursite.com/image.jpg" />
    <meta name="twitter:url" content="https://www.yoursite.com/" />

    <!-- Standard Meta Tags -->
    <!-- Standard meta tags for SEO -->
    <meta name="description" content="Your page description here" />
    <meta name="keywords" content="keyword1, keyword2, keyword3" />

    <!-- Canonical Link -->
    <!-- Canonical URL to prevent duplicate content issues -->
    <link rel="canonical" href="https://www.yoursite.com/your-page" />

    <!-- Schema.org Markup -->
    <!-- Structured data for search engines -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Article",
      "headline": "Your Article Title",
      "image": "URL to your image",
      "author": "Your Name"
    }
    </script>

    <!-- Favicon and Apple Touch Icons -->
    <!-- Icons for browsers and iOS devices -->
    <link rel="icon" href="/path/to/favicon.ico" />
    <link rel="apple-touch-icon" href="/path/to/apple-touch-icon.png" />
```