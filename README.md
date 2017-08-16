# WordPress Dev Utilities

A collection of useful functions for WordPress Development. 

Will be modularised and rolled into a development plugin alongside custom post types, taxonomies and shortcodes modules.

## Features

This plugin includes the following functions:

`function str_contains_substr_util( $haystack, $needle, $encoding = 'UTF-8' );`

`function str_starts_with_util( $haystack, $needle, $encoding = 'UTF-8' );`

`function str_ends_with_util( $haystack, $needle, $encoding = 'UTF-8' );`

`function truncate_to_char_limit_util( $string_to_truncate, $character_limit = 100, $ending_suffix = '', $encoding = 'UTF-8' );`

`function truncate_to_word_limit_util( $string_to_truncate, $word_limit = 100, $ending_characters = '...' );`

`function str_to_lowercase_util( $string_to_convert, $encoding = 'UTF-8' );`

`function str_to_trimmed_array_util( $string_to_convert, $delimiter = ' ' );`

`function flatten_nested_associative_array( $array, $return );`

## Installation

### Using Git Clone

1. In terminal, navigate to `{path to your sandbox project}/wp-content/plugins`.
2. Then type in terminal or Git Bash: `git clone https://github.com/JeffCleverley/WordPress-dev-utilities.git`
4. Log into your WordPress website.
5. Go to Plugins and activate this plugin.

### Downloading

If you do not have git or SSH setup yet, then you can click on the Download button here in this repository.  Install following these steps:

1. Click on the Download button above.
2. Move the zipped file into your project's `{path to your sandbox project}/wp-content/plugins` folder
3. Unzip the file
4. Log into your WordPress website.
5. Go to Plugins and activate this plugin.