# Apple Low Latency Video Player

Welcome to the Apple Low Latency Video Player! This advanced video player harnesses the power of Apple's low-latency technology to provide you with a high-quality streaming experience. With seamless content delivery utilizing QUIC and HTTP/3 protocols, you can enjoy enhanced performance for your video playback.

## Demo

Check out our live demo: [Low Latency HLS Demo](https://low-latency-hls.sariska.io/)

## Features

- **High-Quality Streaming:** Experience video playback in stunning quality with our advanced player.
- **Low-Latency Technology:** Benefit from Apple's cutting-edge low-latency technology for minimal delays.
- **QUIC and HTTP/3 Protocols:** Enjoy seamless content delivery through the latest and most efficient protocols.
- **Easy Integration:** Simply enter your HLS URL, click "Load Video," and immerse yourself in a smooth streaming experience.

## How to Use

1. Open the demo URL: [Low Latency HLS Demo](https://low-latency-hls.sariska.io/)
2. Enter your HLS URL in the provided input box.
3. Click the "Load Video" button to start streaming.
4. Experience high-quality, low-latency video playback.

## Code Overview

This video player is built using HTML, CSS, and JavaScript. It leverages the hls.js library for handling HTTP Live Streaming (HLS). The player includes a user-friendly interface with a simple input box for entering the HLS URL and a button to initiate the video loading process.

```html
<!-- HTML -->
<input type="text" id="hlsUrlInput" placeholder="Enter HLS URL">
<button onclick="loadHls()">Load Video</button>
<video id="video" controls></video>

<!-- JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/hls.js@canary"></script>
<script>
    function loadHls() {
        // JavaScript function for loading HLS video
        // ...
    }
</script>
