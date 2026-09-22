# Purelane Shopify Theme

A production-oriented Shopify implementation of the Purelane plant-based homecare homepage, built for the Troopod AI Product Engineer assignment.

## Overview

The original assignment provided a single-file HTML prototype that was not designed for Shopify.

This implementation converts the prototype into reusable, merchant-editable Shopify theme sections while preserving the original visual direction and interaction patterns.

## Sections

The homepage is implemented using five custom Shopify sections:

- **Purelane Hero**
  - Multiple offer states
  - Shopify product pickers
  - Merchant-editable pricing and offer messaging
  - Auto-rotation with accessible controls
  - Reduced-motion support

- **Product Grid**
  - Merchant-selected Shopify products
  - Real product images, prices and availability
  - Sold-out handling
  - Missing-image fallback
  - Long-title handling
  - Responsive grid

- **Combos**
  - Reusable combination blocks
  - Multiple Shopify product selectors
  - Merchant-editable offer information
  - Horizontal responsive rail
  - Sold-out handling

- **Bundles**
  - Configurable bundle tiers
  - Shopify product data
  - Merchant-editable pricing and messaging
  - Responsive layout
  - Accessible CTA labeling

- **Reviews**
  - Merchant-editable review blocks
  - Product association
  - Responsive review rail
  - CSS-based marquee behavior
  - Reduced-motion fallback

## Shopify Architecture

The implementation follows Shopify's native theme architecture:

```text
assets/
config/
layout/
locales/
sections/
snippets/
templates/