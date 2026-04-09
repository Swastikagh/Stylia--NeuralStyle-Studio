🎨 NeuralStyle Studio

NeuralStyle Studio is a deep learning-based application that transforms images into artistic masterpieces using Neural Style Transfer. Built with TensorFlow, VGG19, and Gradio, it allows users to blend the content of one image with the style of another through an interactive web interface.

🚀 Features
🖼️ Upload content and style images
🎨 Generate stylized artwork using deep learning
⚡ Real-time interaction via Gradio UI
🧠 Uses pre-trained VGG19 for feature extraction
📊 Combines content loss and style loss
🔄 Iterative optimization for high-quality output
🛠️ Tech Stack
Python
TensorFlow / Keras
VGG19 (pre-trained model)
Gradio (UI)
NumPy
Pillow (Image processing)
Matplotlib
📦 Installation

Run the following command to install dependencies:

pip install tensorflow gradio pillow matplotlib
▶️ Usage

Run the script:
python app.py

Then open the Gradio link in your browser.

🧪 How It Works
Load content and style images
Extract features using VGG19
Compute:
Content Loss (preserves structure)
Style Loss (captures artistic patterns using Gram Matrix)
Optimize image using gradient descent
Generate stylized output
🖼️ Input / Output
Input:
Content Image
Style Image
Output:
Stylized Image (artistic blend)
⚙️ Parameters

You can modify:

num_iterations → Quality vs speed
content_weight → Content importance
style_weight → Style intensity
📌 Future Improvements
Add style presets
Faster processing with GPU optimization
Save/download output images
Add multiple style blending
🤝 Contributing

Feel free to fork the repo and submit pull requests to improve the project.

📄 License

This project is open-source and available under the MIT License.
