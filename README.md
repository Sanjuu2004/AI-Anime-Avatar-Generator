# AI-Anime-Avatar-Generator

Transform your photos into anime-style avatars with smooth edges, vibrant colors, and soft shading transitions!
This project uses OpenCV and Matplotlib to cartoonize real-life images, inspired by traditional anime art styles.

<p align="center"> <img src="demo/demo_result.png" width="80%" alt="Anime Avatar Example"/> </p>
✨ Features

✅ Load any image and process it into anime-style output
✅ Soft edges using adaptive thresholding
✅ Smooth shading with Gaussian blur & bilateral filtering
✅ Enhanced colors & vibrancy for an anime feel
✅ Side-by-side comparison of original vs anime avatar

🛠️ Tech Stack

Python 3.x – Core programming language

OpenCV – Image processing & transformations

NumPy – Numerical operations on arrays

Matplotlib – Visualization of original & processed images

📦 Installation

Clone the repository:

git clone https://github.com/Sanjuu2004/AI-Anime-Avatar-Generator.git
cd anime-avatar-generator


Install dependencies:

pip install numpy opencv-python matplotlib

🚀 Usage

Replace the image path inside the generate_anime_avatar() function with your own image file.

Run the script:

python anime_avatar_generator.py


The original image and the anime-style avatar will be displayed side by side.

📂 Code Overview

Load Image → Reads image in RGB format for processing

Smooth Anime Effect →

Gaussian Blur → smooth shading

Adaptive Thresholding → soft edges

Bilateral Filtering → vibrant color enhancement

Display Images → Side-by-side comparison with Matplotlib

🖼️ Example

Input Image:
<img src="demo/input.png" width="40%"/>

Output Anime Avatar:
<img src="demo/output.png" width="40%"/>

🌟 Possible Future Enhancements

🎭 Multiple cartoon styles (Anime, Western Comics, Watercolor, etc.)

🌐 Web interface with Flask/Streamlit for easy uploads

🎨 Custom filters (background changes, overlays, artistic effects)

💾 Export avatars as PNG/SVG for use in profiles or social media

📲 Direct integration with social media APIs for instant sharing

⚡ Performance Optimizations

Use multithreading for faster filtering

Resize large images before processing

Enable GPU acceleration with CuPy or CUDA for heavy workloads

🐛 Troubleshooting

No module named 'cv2' → Run pip install opencv-python

Image not displaying → Check image path & supported formats (PNG, JPG)

Slow processing → Resize high-resolution images before applying effects


