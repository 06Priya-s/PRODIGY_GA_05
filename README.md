# PRODIGY_GA_05
# Neural Style Transfer Implementation
<h2>Project Description</h2>
    <p>
        A Python implementation of Neural Style Transfer using TensorFlow Hub's pre-trained model to apply artistic styles from one image to another.
    </p>
    
<h2>Features</h2>
    <ul>
        <li>🎨 Applies artistic styles from any image to your content photos</li>
        <li>⚡ Fast processing using TensorFlow Hub's pre-trained model</li>
        <li>🖼️ Supports common image formats (JPG, PNG, etc.)</li>
        <li>📏 Automatic image resizing while maintaining aspect ratio</li>
        <li>👁️ Visual output using Matplotlib</li>
    </ul>
    
<h2>How It Works</h2>
    <p>The implementation:</p>
    <ol>
        <li>Loads content and style images with automatic resizing</li>
        <li>Preprocesses images for TensorFlow compatibility</li>
        <li>Uses TF-Hub's <code>magenta/arbitrary-image-stylization-v1-256</code> model</li>
        <li>Converts and displays the stylized output</li>
    </ol>
    
h2>Requirements</h2>
    <pre><code>pip install tensorflow tensorflow_hub pillow numpy matplotlib</code></pre>
    
<h2>Usage</h2>
    <p>Simply replace <code>content.jpg</code> and <code>style.jpg</code> with your image paths:</p>
    <pre><code>content_path = "your_content_image.jpg"
style_path = "your_style_image.jpg"</code></pre>
    
<h2>Example Output</h2>
<p>Before (Content) Image</p>
    <img src="https://github.com/06Priya-s/PRODIGY_GA_05/blob/main/gir%3B.jpg" width="200" alt="Content Image">
    <p>Style Image</p>
    <img src="https://github.com/06Priya-s/PRODIGY_GA_05/blob/main/famous_painting.jpg" width="200" alt="Style Image">
    <p>After (Result)</p>
    <img src="https://github.com/06Priya-s/PRODIGY_GA_05/blob/main/result.png" width="200" alt="Result Image">
    

