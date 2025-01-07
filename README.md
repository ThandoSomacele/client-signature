# Email Signature Generator

A simple HTML-based email signature generator with copy functionality, designed for MCA INC.

## Features

- Clean, professional email signature layout
- Responsive design
- One-click copy functionality
- Email client compatible styling
- Animated banner support (GIF)

## Setup

1. Place the index.html file on your web server
2. Add your banner images/GIF to the server:
   - `/banner-animation.gif` for the animated version
   - `/banners/banner-1.jpg` for the static version

## Usage

1. Open the index.html file in a web browser
2. Click the "Copy Signature" button
3. Paste the signature into your email client's signature settings
4. Modify the personal details as needed:
   - Name
   - Title
   - Website
   - Phone number

## Customization

### Modifying Styles

Key style elements:

- Primary color: `#003366`
- Font family: Arial
- Max width: 600px

### Image Requirements

- Banner dimensions: 600px width
- Format: JPG/GIF
- File path: `/banners/` directory

## Notes

- The signature uses inline styles for maximum email client compatibility
- JavaScript is only used for the copy functionality and is not included in the copied signature
- Some email clients may have restrictions on image sizes and animations

## File Structure

```
├── index.html
├── banners/
│   └── banner-1.jpg
└── banner-animation.gif
```
