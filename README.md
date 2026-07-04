# Brewlore Studio

Brewlore Studio is a lightweight web-based content publishing tool for managing and uploading short-form educational videos about beverage history and culture.

This repository hosts the public static pages required for the Brewlore Studio TikTok Developer app review, including the service introduction, Terms of Service, and Privacy Policy.

## Purpose

Brewlore Studio is designed to help manage short educational videos related to:

- Beverage history
- Whisky culture
- Korean traditional alcohol
- Tequila
- Rum
- Gin
- General drinking culture and historical stories

The tool is intended for educational and cultural content management, not for alcohol sales, alcohol delivery, advertising, or age-restricted commerce.

## TikTok Integration

Brewlore Studio is planned to use TikTok's official developer APIs for user-authorized upload workflows.

The intended integration flow is:

1. The user signs in with TikTok through OAuth.
2. The user selects a local MP4 video file.
3. The app uploads the selected video to the user's TikTok drafts or inbox.
4. The user reviews, edits, and manually publishes the content in TikTok.

The app does not:

- Scrape TikTok
- Create TikTok accounts
- Access unrelated user data
- Publish videos without user action
- Store TikTok passwords
- Sell user data

## Public Pages

- Home: `https://YOUR_GITHUB_ID.github.io/brewlore-studio/`
- Terms of Service: `https://YOUR_GITHUB_ID.github.io/brewlore-studio/terms.html`
- Privacy Policy: `https://YOUR_GITHUB_ID.github.io/brewlore-studio/privacy.html`

## Repository Structure

```text
brewlore-studio/
├── index.html
├── terms.html
├── privacy.html
└── README.md