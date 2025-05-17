# Persian Glyphs Converter

**Description:**  
Persian Glyphs Converter is a PHP library designed to handle the conversion of Persian text into glyph-friendly UTF-8 strings. This library ensures that your Persian text renders correctly in systems requiring specific glyph adjustments.

## Features:
- Converts Persian UTF-8 strings into glyph-friendly formats.
- Lightweight and easy to integrate into any PHP project.
- Supports custom text transformations for titles and content.

## Installation:
1. Download the `Glyphs.php` file and include it in your project directory.
2. Use the following code snippet to initialize and use the library.

## Usage:
Here’s how to use the library in your PHP project:
```php
require __DIR__ . '/Glyphs.php';

$obj = new Persian_Glyphs();
$TitleGlyphed = $obj->utf8Glyphs($Title);

echo $TitleGlyphed; // Outputs the glyph-adjusted string

