# Webform steps

This module makes the progressbar provided by webform clickable.


## Installation

Install this module and its dependencies [like any other Drupal modules](https://www.drupal.org/docs/7/extend/installing-modules).

### Dependencies

* [webform](https://www.drupal.org/project/webform) ≥ 4.0


### Migration from webform3

In order to migrate from webform 3 you have to:

- Install webform≥4.0 and webform_steps 2.x, then run all database upgrades.
- Install webform_steps 3.x, then run all database upgrades.

*It’s not possible to upgrade from webform3/webform_steps 1.x to webform4/webform_steps 3.x directly.*


## Usage

No additional configuration is needed. With this module enabled the steps displayed in the progress bar become clickable automatically.

Note that this module only allows to navigate one step forward at a time.


## Devlopment

Development on this module is happening mainly [on github](https://github.com/moreonion/drupal-webform-steps). Feel free to post issues and pull requests there.

*Note: Development branches on drupal.org might be outdated because they are only pushed to in order to tag releases.*
