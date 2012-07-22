# gerrit-hudson

Cleverly named project which provides a useful `ref-updated` hook for Gerrit
to trigger a Hudson build, or to ping any URL you like.

Requires Python 2, tested on 2.6.5.

## Instructions

Copy `ref-updated` to Gerrit's `hooks` directory, making sure it is
executable. Configure the `refs_urls` dictionary as indicated.
