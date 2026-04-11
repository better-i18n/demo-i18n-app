# Demo i18n App

A demo application for testing [Better i18n](https://better-i18n.com) platform integration.

## Structure

```
locales/
├── en/           # Source language (English)
│   ├── common.json    # Navigation, hero, features, footer
│   ├── auth.json      # Login/signup flows
│   └── dashboard.json # Dashboard UI
├── tr/           # Turkish translations
├── de/           # German translations
└── es/           # Spanish translations
```

## Integration

This repo is connected to Better i18n for:
- Automatic key discovery from source files
- AI-powered translation to target languages
- Translation delivery via CDN
