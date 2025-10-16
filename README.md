## Art Style Transfer using GANs

### 🧠 Project Title
**Generative Adversarial Networks (GANs) for Neural Art Style Transfer**

### 📘 Project Description
Used GANs and CNNs to transfer artistic styles from one image to another. Leveraged **perceptual loss** with VGG networks to combine content and style into high-quality synthetic artwork.

### 🎯 Business Task
- Separate and recombine style and content features  
- Implement a custom perceptual loss function  
- Generate high-resolution style-transferred images  

### 📁 Dataset Summary

| Feature | Description |
|---------|-------------|
| 🖼 Content Images | High-resolution photographs |
| 🎨 Style Images | Famous artworks or abstract patterns |
| 🖥 VGG Network | Pretrained weights used for feature extraction |

**Data Source:** Public domain images & ImageNet VGG weights

### 🧰 Tools & Technologies
Python • PyTorch / TensorFlow • Torchvision / Keras Utilities • NumPy • Pillow (PIL)

### 🧹 Model Architecture & Loss Function
- Neural Style Transfer Network using GAN principles  
- **Perceptual Loss:** `L_total = α * L_content + β * L_style`  
  - Content Loss: distance between generated and content feature maps  
  - Style Loss: distance between Gram matrices of generated and style images  
  - α, β balance content vs. style preservation  

### 📊 Visualizations & Results
- Activation maps showing style/content separation  
- Loss curves showing convergence  
- Gallery of generated artworks combining multiple styles  

### 💡 Strategic Recommendations
- Explore real-time style transfer for video  
- Tune α/β to balance photorealism vs. abstraction  
- Deploy as creative tool for digital artists or marketing content  

---
