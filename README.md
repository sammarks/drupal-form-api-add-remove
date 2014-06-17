# Drupal Form API Add/Remove Example (with AJAX)

This module is an expansion of Drupal's AJAX add more example ([found here](https://api.drupal.org/api/examples/ajax_example%21ajax_example_graceful_degradation.inc/function/ajax_example_add_more/7)).

This example expands it to allow the user to remove specific rows instead of removing just the last row. It also bundles it up into a single module so it's much easier to read.

This repository is meant to serve as an example, and as such isn't intended to be used on a production website.

You could extend this module and add an implementation of `hook_schema` and use `drupal_write_record` to store the contents of the form in the database.
