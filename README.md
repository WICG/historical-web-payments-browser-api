# The Web Payments Browser API

This is a proposal by the Web Payments Community Group for a new browser API
to enable a better payment experience on the Web. The API enables web developers
to register payment instruments (credit card, PayPal, Bitcoin, etc.), initiate
requests for payment, and acknowledge requests for payment.

The live version of this specification can be found [here](http://wicg.github.io/web-payments-browser-api/).

# Problem

Sending and receiving money on the Web is currently a manual process that
requires the sharing of secrets, such as credit card numbers. Not only is
the process not uniform across the same payment methods on different websites,
it is also a major target for phishing and other financial attacks.

# Vision

In general, this proposal attempts to enable a set of standard payment
flows on the Web while also automating a large part of the payment flow.
Where possible, more secure mechanisms for making payments are enabled so
that the end result is a seamless and far more secure payment experience on
the Web.

The full vision of the Web Payments Work at W3C can be found here:

http://www.w3.org/Payments/IG/Vision

# Roadmap

Phase I of the Web Payments Roadmap focuses on enabling basic payment
flows via the browser. Details of this roadmap can be found here:

http://www.w3.org/Payments/IG/Roadmap/#web-payments-phase-1

# Use Cases

There are 17 use cases that we are attempting to partially (or fully) address
in Phase I with this browser API:

http://www.w3.org/Payments/IG/Roadmap/#use-cases

The full list of Web Payments use cases can be found here:

http://www.w3.org/TR/web-payments-use-cases/
