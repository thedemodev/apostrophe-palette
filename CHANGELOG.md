# Changelog

## 2.0.23

* No longer sets the site to the `user` asset scene, which means we no longer push a lot of extra JS and CSS when palette is present for logged out site visitors.

## 2.0.17

* Performance improvements when updating the global doc settings based on the palette.
* Race condition prevention when updating the global doc settings based on the palette.
* Refactoring for maintainability; feature set remains the same.
* Debounced the `palette-update` route to prevent "slamming" of the server.

