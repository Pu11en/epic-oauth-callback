# GOMER Epic OAuth callback

This public page returns an Epic MyChart authorization response directly to the
GOMER plugin running on the same computer.

It forwards only Epic's short-lived `code` or `error` and the state-bound local
callback address. It does not receive Chart data, store credentials, use a
remote relay, or display a code for manual copying.

The source in this repository is intentionally static and contains no secrets.
