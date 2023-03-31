# wishlist
A modern shareable wishlist.

## Resources
i18next
- https://www.i18next.com/
- https://deno.land/x/i18next@v22.4.9
- https://jsfiddle.net/jamuhl/dvk0e8a9/#tabs=js,result,html

deno fresh
- https://fresh.deno.dev/

autofill
- https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete#values
- specifically current-password for login

illustrations
- undraw
- https://dicebear.com/styles/identicon

auth
- https://caddyserver.com/docs/caddyfile/directives/try_files
  - https://stackoverflow.com/questions/75611964/caddyfile-with-multiple-single-page-applications
- https://caddyserver.com/docs/caddyfile/directives/forward_auth
  - API will check if you have access to the private area.
- jwt tokens

There is a public and a private space. The frontpage, login and register page are all public. The wishlist and home is private. It should be possible to view a shared wishlist without having a user.

Storage savings. If you have no interactions with the service in 1.1 years, then your account will be automatically deleted.

## Mechanics
Upon signing up you only give your name. A password and shareable ID will be generated for you. The password is needed if you want access to the account. The shareable ID is meant to be shared with family and friends so that they can see your wishlist. You can not choose your own password or ID, but they can be randomly generated again.
