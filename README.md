# StackPrimer delivery (internal)

These URLs are post-pay redirects from Stripe Payment Links.

Treat thank-you paths and zip URLs as **semi-secret**. They are not a hard paywall: anyone with the URL can download. That is acceptable for this MVP; webhook-gated delivery comes later.

If a path leaks badly, regenerate obscure path segments and update the Stripe Payment Link `after_completion.redirect.url` values.

Do not list zip links on the site root. Do not publish `free.zip` here.
