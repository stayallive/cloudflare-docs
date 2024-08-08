---
title: Phish submissions
pcx_content_type: how-to
weight: 4
---

# Phish submissions

As part of your continuous email security posture, administrators and security analysts need to submit missed {{<glossary-tooltip term_id="phishing">}}phish{{</glossary-tooltip>}} samples to Email Security, so Cloudflare can process them and take necessary action.

Submitting missed phish samples to Cloudflare is of paramount importance and necessary for continuous protection. Submitting missed phish samples helps Cloudflare improve our machine learning (ML) models, and alerts us of new attack vectors before they become prevalent.

## How to submit phish

To submit a phish:

1. Log in to [Zero Trust](https://one.dash.cloudflare.com/).
2. Select **Email Security**.
3. Select **Settings**.
4. Under **Phish submission**, select **View**.

## PhishNet O365

PhishNet is an add-in button that helps users to submit directly to Email Security {{<glossary-tooltip term_id="phishing">}}phish{{</glossary-tooltip>}} samples missed by Email Security's detection. 

To set up PhishNet O365:

1. Log in to the Microsoft admin panel. Go to **Microsoft 365 admin center** > **Settings** > **Integrated Apps**.
2. Select **Upload custom apps**.
3. Choose **Provide link to manifest file** and paste the the following URL:
    ```txt
    https://phishnet-o365.area1cloudflare-webapps.workers.dev?clientId=ODcxNDA0MjMyNDM3NTA4NjQwNDk1Mzc3MDIxNzE0OTcxNTg0Njk5NDEyOTE2NDU5ODQyNjU5NzYzNjYyNDQ3NjEwMzIxODEyMDk1NQ
    ```
4. Verify and complete the wizard.