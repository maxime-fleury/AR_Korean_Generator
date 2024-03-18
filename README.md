# Fake Words Image Generator (AR_Korean_Generator) for AR AI Project

This project aims to generate fake words images for an AR AI project, particularly focusing on the Korean language.

## Files Overview

### `gen.php`

This PHP script generates fake words images by including the `index.php` file in a loop.

### `index.php`

- This PHP script generates random strings of characters.
- It utilizes the `getRandom()` function to create random strings based on a given character set.
- The generated strings are then used to create images using the GD library in PHP.
- The images are saved with filenames in the format `xxxx.png`, where `xxxx` represents a zero-padded numerical ID.

## Usage

1. Ensure you have a web server with PHP support (e.g., Apache with PHP module).
2. Place the `gen.php` and `index.php` files in the appropriate directory accessible by the web server.
3. Access `gen.php` in a web browser to generate the fake words images.
4. The generated images will be saved in the `img/` directory within the project.

## Requirements

- PHP with GD library support
- Web server environment (e.g., Apache)

## License

This project is licensed under the MIT License
