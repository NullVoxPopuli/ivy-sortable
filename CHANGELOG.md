# ivy-sortable

## 1.0.0-beta.5

* Add `handle` option. [@ToddSmithSalter](https://github.com/ToddSmithSalter)
* Upgrade to ember-cli 0.2.7.
* Fix reference to `_parentView`, so action triggering works in Ember 1.13+.
* Pull jQuery UI options into a `uiOptions` concatenated property.

## 1.0.0-beta.4

* Add repo URL to package.json.
* Fix potential Morph errors when the content array is modified.

## 1.0.0-beta.3

* Deprecate the `{{ivy-sortable}}` helper.

## 1.0.0-beta.2

* Check `isDestroying` before refreshing the sortable.

## 1.0.0-beta.1

* Call sortable's `refresh` method after content changes. This fixes an issue
  where the "ui-sortable-handle" class would not be added to newly-inserted
  list items. See [#2](https://github.com/IvyApp/ivy-sortable/issues/2) for
  further details.

## 0.3.0

* Remove version suffix from ivy-sortable.js.

## 0.2.1

* Add jQuery UI Sortable option bindings.
* Upgrade to ember-cli 0.1.5.
* Remove unnecessary ember-data dependency in dummy app.
* Upgrade to ember 1.9.1 in dummy app.

## 0.2.0

* Convert to an ember-cli addon.

## 0.1.0

* Initial release.
