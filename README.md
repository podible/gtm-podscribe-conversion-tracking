# Podscribe Conversion Tracking Template for Google Tag Manager

![Podscribe Logo](https://images.squarespace-cdn.com/content/v1/60fdad6fb704f7471c09aed5/5f3574f3-02e7-40ef-a62c-7bce3e5850fa/Group+611.png?format=100w)

## Overview

The Podscribe Tag Template for Google Tag Manager enables advertisers to implement attribution for podcast advertising campaigns. This template provides a straightforward method to track website conversions and attribute them to podcast ad exposures through Podscribe's attribution platform.

## Features

- Track multiple conversion events: pageviews, purchases, leads, and signups
- Support for transaction values and order IDs
- Discount/promo code tracking
- Privacy-compliant tracking with hashed emails
- Easy configuration with clear field descriptions

## Requirements

- A Google Tag Manager account
- Podscribe advertiser name (provided by Podscribe)
- Podscribe User ID (provided by Podscribe)

## Installation

### From the GTM Template Gallery

1. In Google Tag Manager, navigate to **Templates**
2. Click **Search Gallery** in the Tag Templates section
3. Search for "Podscribe"
4. Click on the Podscribe template
5. Click **Add to workspace**

### Manual Installation

1. Download the [template.tpl](template/template.tpl) file from this repository
2. In Google Tag Manager, navigate to **Templates**
3. Click **New** under the Tag Templates section
4. Click the menu (︙) in the top right corner and select **Import**
5. Select the downloaded template file
6. Click **Save**

## Configuration

### Basic Settings

- **Podscribe Advertiser**: Your unique advertiser name provided by Podscribe
- **Podscribe User ID**: Your UUID provided by Podscribe
- **Tracking Event Type**: Select the type of event to track:
  - `view`: Page view event
  - `purchase`: Purchase or transaction event
  - `signup`: User registration/account creation
  - `lead`: Lead generation event

### Advanced Settings

#### For Purchase, Signup, and Lead Events

- **User Hashed Email**: SHA-256 hashed email address (recommended for cross-device attribution)
- **Device ID**: Optional unique identifier for the device (auto-generated if not provided)

#### Event-Specific Parameters

- **Revenue Value**: Monetary value of the purchase or lead
- **Order Number**: Transaction or order ID
- **Discount Code**: Promo or discount code used
- **Product or Service**: Name of the product or service

## Privacy Compliance

- The template is designed with privacy in mind
- Email addresses should be hashed using SHA-256 before being passed to the template

## Support

For questions or assistance, please contact:
- Email: adops@podscribe.com
- Website: [podscribe.com](https://podscribe.com)


## About Podscribe

Podscribe is a podcast attribution platform that helps advertisers measure the effectiveness of their podcast advertising campaigns. By connecting podcast ad exposures to website conversions, Podscribe provides insights on ROAS and helps optimize podcast advertising strategies.
