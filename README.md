# 69s Film Camera App

This is a simple web-based camera application that applies a 69s film camera filter to your camera feed using a LUT (Lookup Table) PNG image. The app is entirely contained in a single HTML file, making it lightweight and easy to use.

### Features

- Access your device's camera feed directly in the browser.
- Turn Flash ON/OFF.
- Applies a vintage 90s film camera effect using a LUT image.
- Save the filtered Image.
- Simple and minimalistic design.
- No external dependencies, everything is built into one HTML file.

### Todo
- [ ] More Filters
- [ ] Flip Camera

### Demo

https://69scamera.netlify.app/

### How It Works

The app uses your device's camera stream and applies a 90s-style film effect using a LUT (Lookup Table) PNG image. This image transforms the colors of the camera feed to create a vintage effect.
Then using fast xorshifting algorithm for fast noise.

### Requirements

- A web browser that supports HTML5 and camera access.
- Permission to access your camera.

### LUT Image

The LUT PNG file is responsible for transforming the colors in the camera feed. It gives the 90s film camera aesthetic. If you want to customize the effect, you can replace the LUT image with another PNG file.

### Customization

- **Change LUT PNG**: Replace the existing LUT PNG in the code to modify the filter effect.
- **Further Customization**: You can tweak the CSS or JS within the HTML file to adjust the filter intensity or add additional effects.

