
# Fullscreen Image Slideshow

A simple, elegant fullscreen image slideshow web application optimized for portrait (1080x1920) images with smooth fade transitions.

## Features

- Fullscreen display with black background
- Smooth fade transitions between images (1-second duration)
- 5-minute display time per image
- Automatic cycling through images
- Responsive design that maintains aspect ratio
- Portrait orientation optimization (1080x1920)
- Zero dependencies - pure HTML, CSS, and JavaScript

## Directory Structure

```
slideshow/
  ├── index.html
  └── images/
      ├── image1.jpg
      ├── image2.jpg
      ├── image3.jpg
      ├── image4.jpg
      └── image5.jpg
```

## Setup

1. Clone the repository:
```bash
git clone https://github.com/linktoken/HTML-Portrait-Slideshow
```

2. Place your images in the `images` folder
   - Name them sequentially: image1.jpg, image2.jpg, etc.
   - Recommended image resolution: 1080x1920 (portrait)

3. Open `index.html` in a web browser

## Customization

### Changing Transition Timing
To modify the fade transition duration, update the CSS transition property in the `style` section:
```css
img {
    transition: opacity 1s ease-in-out;
}
```

### Adjusting Display Duration
To change how long each image is displayed, modify the timeout value in the JavaScript (currently set to 5 minutes):
```javascript
setTimeout(changeImage, 5 * 60 * 1000); // 5 minutes per image
```



## Author

Your Name - [@linktoken](https://github.com/linktoken)

## Acknowledgments

- Inspired by the need for a simple, dependency-free image slideshow solution
- Thanks to all contributors who help improve this project
