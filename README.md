# Drupal8 layouts
## Example module with plugin to create custom layouts in Drupal 8

These custom layouts can then be used to create panel pages with page manager or as part of a variant configuration to display a node.

### Custom template configurations
This module includes an implementation of a set of fields that can be used in the layout configuration to customize the region wrappers and css classes used in the template.

### Considerations

- The templates included in this module use the Zurb Foundation's grid system but can easily be adapted to any other grid system or styling.
- This module uses the layout API and registers the layouts using the *_layouts.info.yml file

More information here https://www.drupal.org/docs/8/api/layout-api/how-to-register-layouts
