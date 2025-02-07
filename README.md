# Computer Vision : Image Processing

## 📋 Project Overview
This project was developed as part of the first practical work (TP1) in artificial vision and image processing. The goal was to implement fundamental techniques such as convolution, non-linear filtering, and result analysis using Python libraries.

## 🚀 Features
- **Image Loading & Preprocessing:** Converting images to grayscale and matrix representation.
- **Convolution Implementation:** Applying filters like blur (3x3 & 5x5), edge detection (Laplacian), and sharpening.
- **Non-Linear Filtering:** Median filtering to reduce impulse noise (salt and pepper).
- **Result Analysis:** Comparing the effectiveness of different filters in noise reduction and edge preservation.

## 🛠️ Technologies Used
- **Python** 🐍
- **NumPy:** Matrix manipulations
- **Matplotlib:** Image visualization
- **PIL:** Image loading and basic processing
- **OpenCV (optional):** Advanced image processing

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/AnisBenini/Computer-Vision-Image-Processing.git

# Navigate to the project directory
cd Computer-Vision-Image-Processing

# Install required libraries
pip install numpy matplotlib pillow opencv-python
```

## 🖼️ How to Use
1. Run the Jupyter Notebook:
```bash
jupyter notebook TP1-VA.ipynb
```
2. Follow the notebook to:
   - Load images from the folder img
   - Apply convolution filters
   - Perform median filtering
   - Compare the results

## 📊 Results & Analysis
- **Blur (3x3 & 5x5):** Reduces noise but slightly blurs fine details.
- **Laplacian Filter:** Highlights edges but amplifies noise.
- **Sharpening:** Enhances details but may increase noise.
- **Median Filter:** Most effective for impulse noise, preserving edges well.

## ⚡ Challenges Faced
- Edge handling issues during convolution (padding artifacts).
- Noise amplification with certain filters.
- Optimization of kernel sizes for different effects.

## 💡 Future Improvements
- Experiment with different kernel sizes and padding techniques.
- Apply preprocessing to reduce noise before sensitive filters.
- Test advanced filtering methods for better edge and noise management.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ for Computer Vision & Image Processing enthusiasts!

