# Advanced QR Code Generator

A powerful, completely offline QR code generator with professional design presets and extensive customization options.

## 🌐 Live Demo
**Try it now:** [https://iamsamk.github.io/QR/](https://iamsamk.github.io/QR/)

## ✨ Features

### 🎨 **8 Professional Presets**
- **Classic** - Traditional black and white
- **Professional** - Sleek black background with white pattern
- **Modern** - Clean contemporary design
- **Neon** - Vibrant cyan glow effect
- **Vintage** - Warm sepia tones
- **Minimal** - Ultra-clean aesthetic
- **Dark Mode** - Perfect for dark themes
- **Creative** - Eye-catching gradient design

### 🎛️ **Advanced Customization**
✅ **Custom Colors** - Full color picker for background and pattern  
✅ **Gradient Support** - Linear and radial gradients with multiple directions  
✅ **Dot Size Control** - Adjustable from 20% to 100% for perfect sizing  
✅ **Shape Styles** - Square, rounded, circle, and diamond patterns  
✅ **Corner Styles** - Square, rounded, extra-rounded, and dot corners  
✅ **Size Control** - Scalable from 200px to 800px  
✅ **Center Image Support** - Add logos with adjustable size (10-30%)  
✅ **Real-time Preview** - Instant updates as you customize  
✅ **Download Support** - High-quality PNG export  
✅ **Offline Functionality** - Works completely without internet  
✅ **Mobile Responsive** - Perfect on all devices

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
