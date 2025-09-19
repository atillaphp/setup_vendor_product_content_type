# Setup Vendor Product Content Type Recipe

A Drupal recipe to set up vendor product content type

## Description

This recipe creates a vendor product content type as an intermeditiary content type for commerce products. Commerce products and variations will be created from vendor product type.

## Installation

To use this recipe in your Drupal project:

1. Require the recipe in your composer.json:

   ```json
   "require": {
       "atillaphp/setup_vendor_product_type": "*"
   }
   ```

2. Run `composer update` to install the recipe.

3. Apply the recipe:
   ```bash
   drush recipe recipes/setup_vendor_product_type
   ```

## Requirements

- Drupal 11+

## Configuration

The recipe imports the following configuration:

- Enables block, help, gin_login and gin_toolbar modules

## License

GPL-2.0-or-later
