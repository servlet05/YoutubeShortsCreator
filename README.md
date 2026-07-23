# YoutubeShortsCreator
YouTubeShortsCreator
🎬 Multi Image and Audio to MP4 YouTube Shorts Creator
📖 Overview

YouTubeShortsCreator is a progressive web application (PWA) that enables massive and automated generation of YouTube Shorts, TikTok, or Reels-style videos. The tool combines images and audio files to create vertical format videos (1080x1920) ready for short-form content platforms.
✨ Key Features
🎯 Intelligent Mass Generation

    Batch processing: Generate multiple videos simultaneously directly in your browser

    Random assignment: Combines images and audios randomly without repetitions

    Full control: Define exactly how many videos you want to generate

    No limits: Process as many images and audios as you desire

🎨 Video Customization

    Adjustable duration: Configure each video's length (3-120 seconds)

    Loop mode: Enable/disable continuous audio playback

    Optimized format: Vertical videos at 1080x1920 (9:16 aspect ratio)

    Multiple codecs: Support for H.264, VP8, VP9, and more

📊 File Management

    Mass upload: Drag and drop multiple files at once

    Extended support:

        Images: PNG, JPG, WEBP, BMP, GIF

        Audio: MP3, OGG, WAV, M4A, AAC

    Preview: View each generated video before downloading

    Individual or batch download: Download videos one by one or all together

🛡️ Privacy & Security

    100% local: All processing occurs in your browser

    No servers: Files are never uploaded to the internet

    No storage: No data is saved on any server

🚀 How to Use
1. File Preparation
bash

📁 Images Folder/
├── image1.jpg
├── image2.png
└── image3.webp

📁 Audio Folder/
├── audio1.mp3
├── audio2.ogg
└── audio3.wav

2. File Upload

    Drag images to the "Images" zone or click to select multiple files

    Drag audios to the "Audios" zone or click to select multiple files

    The app will automatically display the count of loaded files

3. Configuration

    Video count: Define how many shorts you want to generate (maximum: min(images, audios))

    Duration: Adjust duration in seconds (3-120)

    Loop: Enable if you want the audio to repeat when shorter than duration

4. Generation

    Click "Generate Videos"

    Watch real-time progress

    Videos will automatically appear in the grid

5. Download

    Individual: Click "Download" under each video

    Batch: Use the "Download All" button to get all videos at once

🛠️ Technologies Used
Technology	Usage
HTML5	Application structure
CSS3	Styling and responsive design
Vanilla JavaScript	Business logic and processing
Canvas API	Image rendering and composition
MediaRecorder API	Video recording and encoding
Web Audio API	Audio processing and mixing
Drag & Drop API	Intuitive file upload
📋 System Requirements
Compatible Browsers

    ✅ Google Chrome (recommended)

    ✅ Mozilla Firefox

    ✅ Microsoft Edge

    ✅ Opera

    ✅ Brave

Minimum Requirements

    Modern browser with MediaRecorder API support

    Sufficient RAM for video processing (recommended: 4GB+)

    Stable internet connection (only for initial load)

🎯 Use Cases

    Content creators: Generate multiple Shorts for different platforms

    Social media managers: Create batch content for campaigns

    Marketers: Produce promotional videos quickly

    Educators: Create educational content in short format

    Artists: Showcase artwork with background music

💡 Tips & Best Practices
Image Recommendations

    Resolution: Use high-resolution images (at least 1080x1920)

    Aspect ratio: 9:16 for best results

    Format: PNG or JPG for optimal quality

    Content: Centered subjects work best for vertical format

Audio Recommendations

    Format: MP3 or M4A for best compatibility

    Duration: Match video duration or enable loop

    Quality: 128kbps or higher for clear audio

    Volume: Normalize audio levels for consistency

Performance Tips

    Process 10-20 videos per batch for optimal performance

    Close other browser tabs during generation

    Use modern browsers for better encoding speed

    Consider your system's RAM when processing large batches

🔧 Troubleshooting
Issue	Solution
Videos not generating	Check browser console for errors
Slow processing	Reduce video count or close other apps
Audio not syncing	Check if audio format is supported
Black video output	Verify image is loaded correctly
Download fails	Try using "Download All" or individual downloads
🚀 Future Enhancements

    □

    Add text overlay support
    □

    Implement video trimming
    □

    Add transition effects
    □

    Support for custom resolutions
    □

    Export project settings
    □

    Keyboard shortcuts
    □

    Dark/Light theme toggle
    □

    Mobile PWA support

📝 License

This project is open-source and available under the MIT License.
🤝 Contributing

Contributions are welcome! Feel free to:

    Report bugs

    Suggest features

    Submit pull requests

    Improve documentation

📧 Contact

For questions, suggestions, or support, please open an issue on GitHub.

Made with ❤️ for content creators worldwide
