# Stripe Elements examples

[See them in action!](https://stripe.github.io/elements-examples)

This repository contains examples of stylish forms that use Stripe Elements. These examples illustrate how to handle errors in real-time and style focus states, error states, and placeholders.

## Need help with Elements?

- Get started with Stripe Elements by [reading our quickstart guide](https://stripe.com/docs/stripe-js/elements/quickstart).
- For help with Elements and your Stripe integration in general, please [contact Stripe Support](https://support.stripe.com/).


# In this repo

Common code for handling errors and form submission lives [here](js/index.js).

## stripeSite 1

- [JavaScript](js/example1.js)
- [CSS](css/example1.css)

stripeSite 1 shows a form that uses the `card` Element, a custom web font, and a solid icon with a custom color.

## stripeSite 2

- [JavaScript](js/example2.js)
- [CSS](css/example2.css)

stripeSite 2 shows a "floaty-label" form that uses individual `cardNumber`, `cardExpiry`, and `cardCvc` Elements with a custom web font.

The form also collects address (and thus postal code) outside of the payment form. It passes the postal code to Stripe on tokenization.

## stripeSite 3

- [JavaScript](js/example3.js)
- [CSS](css/example3.css)

stripeSite 3 shows a form that uses individual `cardNumber`, `cardExpiry`, and `cardCvc` Elements with a custom web font.

The form also collects postal code outside of the payment form.

## stripeSite 4

- [JavaScript](js/example4.js)
- [CSS](css/example4.css)

stripeSite 4 shows a form that uses the `paymentRequestButton` Element to provide
Apple Pay / Payment Request API support, as well as a `card` Element with a
custom web font.

## stripeSite 5

- [JavaScript](js/dciStripe.js)
- [CSS](css/dciStripe.css)

stripeSite 5 shows a form that uses the `paymentRequestButton` Element to provide
Apple Pay / Payment Request API support, as well as a `card` Element with a
custom icon color.
