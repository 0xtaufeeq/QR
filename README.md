# Advanced QR Code Generator

A powerful, customizable QR code generator that works offline with support for custom colors and center images.

## Features

✅ **URL to QR Code Conversion** - Convert any URL into a QR code instantly
✅ **Custom Colors** - Customize both background and pattern colors
✅ **Adjustable Size** - Choose QR code size from 200px to 800px
✅ **Center Image Support** - Add a logo or image in the center of the QR code
✅ **Real-time Preview** - See changes instantly as you customize
✅ **Download Support** - Download QR codes as PNG images
✅ **Offline Functionality** - Works completely offline after first load
✅ **Responsive Design** - Works on desktop, tablet, and mobile devices
✅ **Input Validation** - Automatic URL validation and correction

## How to Use

1. **Open the Application**
   - Open `index.html` in any modern web browser
   - The app will work immediately without any server setup

2. **Enter a URL**
   - Type or paste any URL in the input field
   - The app will automatically validate and fix URLs (adds https:// if missing)

3. **Customize Colors**
   - Use the color pickers to change background and pattern colors
   - Colors update in real-time

4. **Adjust Size**
   - Use the size slider to make the QR code larger or smaller
   - Range: 200px to 800px

5. **Add Center Image (Optional)**
   - Click "Choose File" to upload an image
   - Adjust the image size with the slider (10-30% of QR code size)
   - The image will be displayed in a circle with a border

6. **Download**
   - Click "Download QR Code" to save as PNG
   - Files are saved as "qr-code.png"

## Keyboard Shortcuts

- **Ctrl + Enter**: Generate QR code

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Technical Details

- Uses a **completely local QR code implementation** - no external dependencies!
- Canvas-based rendering for high quality output
- Service Worker for offline functionality
- No server required - runs completely in the browser
- No internet connection needed after initial page load
- Error correction level: Medium (supports center images)
- Supports QR code types 1-10 (handles most URLs and text)

## File Structure

```
QR/
├── index.html      # Main HTML file
├── styles.css      # Styling and responsive design
├── script.js       # Main JavaScript logic
├── qr-core.js      # Local QR code generation library
├── sw.js          # Service Worker for offline support
└── README.md      # This file
```

## Customization

You can easily customize the app by modifying:

- **Colors**: Default colors in the HTML color inputs
- **Size limits**: Min/max values in the size slider
- **Styling**: CSS variables and classes in styles.css
- **Features**: JavaScript functionality in script.js

## Security & Privacy

- **100% Local Processing** - No data is sent to external servers
- All QR code generation happens locally in your browser
- URLs and images never leave your device
- **No internet connection required** after initial page load
- Complete privacy and security

## Troubleshooting

**QR Code not generating?**
- Make sure you've entered a valid URL
- Try adding "https://" to the beginning

**Center image not showing?**
- Ensure the image file is a valid format (PNG, JPG, GIF)
- Try reducing the image size percentage

**Download not working?**
- Make sure you've generated a QR code first
- Check your browser's download permissions

## License

This project is open source and free to use for any purpose.

## Support

If you encounter any issues, please check that:
1. You're using a modern web browser
2. JavaScript is enabled
3. You have a stable internet connection for the initial load
