# Image Placeholder API Documentation

## API Endpoint
The API endpoint for generating placeholder images is:
`https://img.xpo.dev/{width}x{height}`

This will generate a placeholder image with the specified width and height.

For example:
- [https://img.xpo.dev/300x200](https://img.xpo.dev/300x200) - Generates a 300x200 pixels image.
- [https://img.xpo.dev/200](https://img.xpo.dev/200) - Generates a 200x200 pixels image.

## API Limitations
There are a few limitations and potential errors to note:
- The maximum image size is 15000x15000 pixels. If the requested size exceeds the maximum, an error will be returned.
- If the requested size is invalid, such as having negative values or not following the format `{width}x{height}`, an error will be returned.

## Error Responses
If an error occurs, the API will respond with an appropriate error message. The response will have a JSON format:
```json
{
  "error": "Error message"
}
```

## Example
Here's an example of using the Image Placeholder API:
```html
<img src="https://img.xpo.dev/400x300" alt="Example Image" class="example-img" width="400" height="300">
```
![Example Image](https://img.xpo.dev/400x300)

---

## Submitting Issues
If you encounter any issues or have suggestions for improvement, please submit them on the [GitHub issue tracker](https://github.com/xpodev/image-server-docs/issues) for this project.

---

