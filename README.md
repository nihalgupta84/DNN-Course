# 🧠 Deep Neural Networks Course

A comprehensive interactive learning platform for Deep Neural Networks, covering everything from neural network fundamentals to transformers, autoencoders, and generative models.

## 📚 Course Overview

This platform provides an in-depth exploration of modern deep learning architectures with:

- **Interactive Visualizations** — Understand concepts through visual representations
- **Mathematical Foundations** — Detailed derivations and explanations
- **PyTorch Implementations** — Hands-on code examples for every concept
- **Modern UI/UX** — Beautiful, responsive design with dark/light themes

## 🎯 Course Modules

### Module I: Introduction to Deep Learning and Its Applications (20%)
*Coming Soon*

**Topics Covered:**
- Introduction and applications of deep learning in healthcare, time-series analysis, computer vision, social media, marketing, banking, and other sectors
- Biological inspiration behind neural networks
- Neuron model—Perceptron
- Multilayer Perceptron (MLP) and feedforward architecture
- Activation functions
- Training neural networks—Gradient Descent (Stochastic and Batch)
- Backpropagation algorithm

### Module II: Model Parameter Optimization (20%)
*Coming Soon*

**Topics Covered:**
- Loss functions and performance measures for regression and classification tasks
- Overfitting and underfitting, bias-variance trade-off
- Data augmentation, early stopping, regularization (L1, L2, Dropout)
- Optimizers (RMSprop, Adam, etc.)
- Batch normalization
- Hyperparameter tuning (learning rate, batch size, number of hidden layers)

### Module III: Convolutional Neural Networks and Transfer Learning (20%) ✅
*Available Now*

**Topics Covered:**
- Basics of convolution operation, kernels, 1D/2D/3D convolutions
- Parameter sharing, receptive field, pooling, stride, padding
- Popular CNN architectures: LeNet, AlexNet, VGG-Net, ResNet, DenseNet, GoogleNet
- Transfer learning and fine-tuning

**Pages:**
- Convolution Operations
- CNN Parameters (Stride, Padding, Pooling)
- CNN Architectures (LeNet to DenseNet)
- Transfer Learning & Fine-Tuning

### Module IV: Sequential Models and Recurrent Neural Networks (20%) ✅
*Available Now*

**Topics Covered:**
- Introduction to RNNs and their applications
- Long Short-Term Memory (LSTM) networks and Gated Recurrent Units (GRUs)
- Sequence-to-sequence models for natural language processing
- Applications in speech recognition, machine translation, and video analysis
- Attention mechanism
- Transformers

**Pages:**
- Vanilla RNNs
- LSTM & GRU
- Seq2Seq Models with Attention
- Transformer Architecture

### Module V: Autoencoders and Generative Networks (20%)
*Coming Soon*

**Topics Covered:**
- Autoencoders
- Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs)
- GAN architectures (e.g., DCGAN, CycleGAN)
- Image generation with GANs
- Applications of generative models in computer vision and data augmentation

## 🚀 Deployment on Vercel

### Prerequisites

1. A [Vercel account](https://vercel.com/signup) (free)
2. [Vercel CLI](https://vercel.com/cli) installed (optional, for local deployment)
3. Git repository (GitHub, GitLab, or Bitbucket)

### Option 1: Deploy via GitHub (Recommended)

1. **Push your code to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Deep Neural Networks Course"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/dnn-course.git
   git push -u origin main
   ```

2. **Connect to Vercel:**
   - Go to [vercel.com/new](https://vercel.com/new)
   - Import your GitHub repository
   - Vercel will automatically detect the configuration from `vercel.json`
   - Click **Deploy**

3. **Done!** Your site will be live at `https://your-project.vercel.app`

### Option 2: Deploy via Vercel CLI

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel:**
   ```bash
   vercel login
   ```

3. **Deploy:**
   ```bash
   cd "c:\Users\nihal\OneDrive\Documents\AMITY\dnn web\dnn"
   vercel
   ```

4. **Follow the prompts:**
   - Set up and deploy: `Y`
   - Which scope: Choose your account
   - Link to existing project: `N`
   - Project name: `dnn-course` (or your preferred name)
   - Directory: `./`
   - Override settings: `N`

5. **Production deployment:**
   ```bash
   vercel --prod
   ```

### Option 3: Deploy via Vercel Dashboard

1. Go to [vercel.com/new](https://vercel.com/new)
2. Select **"Browse"** and upload your project folder
3. Vercel will detect `vercel.json` and deploy automatically

## 🛠️ Local Development

To run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/dnn-course.git
   cd dnn-course
   ```

2. **Open with a local server:**
   
   Using Python:
   ```bash
   python -m http.server 8000
   ```
   
   Using Node.js:
   ```bash
   npx http-server
   ```
   
   Using VS Code:
   - Install "Live Server" extension
   - Right-click `index.html` → "Open with Live Server"

3. **Access in browser:**
   ```
   http://localhost:8000
   ```

## 📁 Project Structure

```
dnn/
├── index.html                    # Main landing page
├── vercel.json                   # Vercel configuration
├── README.md                     # This file
├── module 1/                     # Coming soon
│   └── index.html
├── module 2/                     # Coming soon
│   └── index.html
├── module 3/                     # CNN module
│   ├── index.html
│   ├── module_3_convolution_operations.html
│   ├── module_3_cnn_params.html
│   ├── module_3_cnn_architectures.html
│   └── module_3_transfer_learning.html
├── module 4/                     # Sequential models module
│   ├── index.html
│   ├── rnn_vanilla_rnns.html
│   ├── lstm_gru.html
│   ├── seq2seq_attention.html
│   └── transformer.html
└── module 5/                     # Coming soon
    └── index.html
```

## ✨ Features

- **🌓 Dark/Light Theme** — Toggle between themes with persistent preference
- **📱 Fully Responsive** — Works seamlessly on desktop, tablet, and mobile
- **🎨 Modern Design** — Clean, professional UI with smooth animations
- **🔍 SEO Optimized** — Proper meta tags and semantic HTML
- **⚡ Fast Loading** — Optimized static site with minimal dependencies
- **🎯 Interactive Navigation** — Easy module and topic navigation
- **📊 Code Examples** — Syntax-highlighted PyTorch implementations

## 🔧 Configuration

### Custom Domain

To add a custom domain in Vercel:

1. Go to your project dashboard
2. Navigate to **Settings** → **Domains**
3. Add your custom domain
4. Update DNS records as instructed

### Environment Variables

Currently, this is a static site with no environment variables needed. If you add backend functionality in the future:

1. Go to **Settings** → **Environment Variables**
2. Add your variables
3. Redeploy the project

## 🤝 Contributing

This is an educational project for Amity University. If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is created for educational purposes as part of the Deep Neural Networks course at Amity University.

## 👨‍💻 Author

**Nihal**  
Amity University  
2024-2025 Academic Year

## 🙏 Acknowledgments

- Course materials and structure based on Deep Neural Networks curriculum
- Design inspiration from modern educational platforms
- PyTorch community for code examples and best practices

## 📧 Support

For questions or issues:
- Open an issue on GitHub
- Contact through Amity University portal
- Email: [your-email@amity.edu]

---

**Happy Learning! 🚀**

Made with ❤️ for deep learning enthusiasts
