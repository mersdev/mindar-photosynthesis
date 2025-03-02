# AR Photosynthesis Educational Experience

An interactive Augmented Reality (AR) educational application that brings photosynthesis to life through immersive visualization. Built with MindAR and A-Frame, this web-based AR experience helps students better understand the photosynthesis process.

## Features

- Interactive AR visualization of photosynthesis process
- Modern, elegant UI with a nature-inspired color scheme
- Real-time image tracking using MindAR
- Mobile-responsive design
- Intuitive play/pause controls
- Educational content delivery through AR

## Prerequisites

- A modern web browser with WebAR support
- A webcam or mobile device camera
- Local development server (for testing)

## Setup

1. Clone this repository:
   ```bash
   git clone [your-repository-url]
   cd mindar-photosynthesis
   ```

2. Serve the files using a local web server. You can use any of these methods:
   - Python: `python -m http.server 8000`
   - Node.js: `npx http-server`
   - PHP: `php -S localhost:8000`

3. Open your browser and navigate to `http://localhost:8000`

## Usage

1. Point your camera at the target image (520.png)
2. The educational AR content will automatically play when the target is detected
3. Use the play button if the video appears black on mobile devices
4. The content will pause when the target is lost from view

## Project Structure

```
├── index.html          # Main application with AR implementation
├── 520.mp4            # Educational video content
├── 520.png            # Target image for AR tracking
├── logo.png           # Application logo
└── targets.mind       # Compiled target image data
```

## Technologies Used

- [MindAR](https://github.com/hiukim/mind-ar-js) - Web AR library for image tracking
- [A-Frame](https://aframe.io/) - Web VR framework for 3D/AR scenes
- HTML5 Video - For educational content delivery
- Modern CSS - For elegant, responsive UI design

## Contributing

Contributions to improve the educational experience or extend the AR functionality are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).