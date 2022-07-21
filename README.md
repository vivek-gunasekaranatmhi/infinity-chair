# FURNI client-only Checkout page

This is an example of a client-only (server-free) purchase page that can be hosted on GitHub using Stripe Checkout.

## Setup

- If you haven't already, create a Stripe Account: https://dashboard.stripe.com/register
- Enable client-only checkout: https://dashboard.stripe.com/account/checkout/settings
- Create a one-time or recurring product in the Stripe Dashboard: https://dashboard.stripe.com/products
  - After creation click the "Use with checkout" button and copy the price ID
  - Paste the IDs into the button `data-price-id` attributes.
- Copy your publishable key from: https://dashboard.stripe.com/apikeys and set it as the value for `PUBLISHABLE_KEY` in the index.html file

## Source

This project is based on a Stripe sample which you can [view here](https://github.com/stripe-samples/github-pages-stripe-checkout).

You can see this repository running on [GitHub Pages](https://pages.github.com/) here: https://stripe-samples.github.io/github-pages-stripe-checkout