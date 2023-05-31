# Image API

This website provides a simple and convenient way to generate placeholder images with custom dimensions. You can easily specify the width and height of the image you need by appending the desired dimensions to the website URL.

## Usage

The URL format for generating placeholder images is as follows:

```
https://img.xpo.dev/{width}x{height}
```

- Replace `{width}` with the desired width of the image in pixels.
- Replace `{height}` with the desired height of the image in pixels.

If you only specify one dimension, the image will be a square with that dimension.

## Default Size

If you don't specify any dimensions in the URL, the default size for the placeholder image is 150x150 pixels.

## Maximum Size

The maximum allowed dimensions for the generated images are 15000x15000 pixels. If you exceed this limit, the image will not be generated, and you will receive an error.

## Examples

Here are two examples demonstrating how to use the Img.xpo.dev API:

1. To generate a placeholder image with dimensions 300x400 pixels, use the following URL:
   ```
   https://img.xpo.dev/300x400
   ```
   This will generate an image that is 300 pixels wide and 400 pixels tall.

   ![300 x 400 image](https://img.xpo.dev/300x400)

2. If you want a square placeholder image with dimensions 500x500 pixels, you can use the following URL:
   ```
   https://img.xpo.dev/500
   ```
   This will generate a square image that is 500 pixels wide and 500 pixels tall.

   ![500 x 500 image](https://img.xpo.dev/500)


That's it! You can now easily generate placeholder images with custom dimensions using the img.xpo.dev API. Enjoy!
