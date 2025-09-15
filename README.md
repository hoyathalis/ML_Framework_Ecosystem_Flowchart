# ML/AI Framework Ecosystem Flowchart

[![Live Website](https://img.shields.io/badge/🌐_Live_Website-Visit-blue?style=for-the-badge)](https://hoyathalis.github.io/ML_Framework_Ecosystem_Flowchart/)
[![GitHub Pages](https://img.shields.io/github/deployments/hoyathalis/ML_Framework_Ecosystem_Flowchart/github-pages?label=Deployment&style=for-the-badge)](https://github.com/hoyathalis/ML_Framework_Ecosystem_Flowchart/deployments)
[![License](https://img.shields.io/github/license/hoyathalis/ML_Framework_Ecosystem_Flowchart?style=for-the-badge)](LICENSE)

> **🚨 Accuracy Notice**: This diagram aims to provide a comprehensive overview of the ML/AI framework ecosystem. However, the landscape evolves rapidly and some connections or details might be outdated or incomplete. Please verify information independently and refer to official documentation for the most current details.

## Overview

An **interactive web-based flowchart** that maps the complete journey of machine learning frameworks from high-level Python code to optimized hardware execution. This comprehensive guide visualizes how popular frameworks like PyTorch, TensorFlow, and JAX transform into efficient code running on CPUs, GPUs, TPUs, and specialized AI accelerators.

## 🌟 Features

### 🎯 **Interactive Diagram**
- **Full-screen responsive** Mermaid.js flowchart
- **Zoom and Pan** - Mouse wheel zoom, click-and-drag navigation
- **Touch Support** - Pinch-to-zoom and drag on mobile devices
- **Keyboard Shortcuts** - Ctrl/Cmd + +/- for zoom, Ctrl/Cmd + 0 to reset
- **Fullscreen Mode** - Dedicated fullscreen view for detailed exploration

### 🎨 **Professional Design**
- **Light/Dark Mode** - Automatic theme switching with persistent preferences
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile
- **Modern UI** - Clean, professional interface with smooth animations
- **Accessibility** - ARIA labels, semantic HTML, keyboard navigation

### 📚 **Comprehensive Content**
- **5-Layer Architecture** - Detailed breakdown of each ecosystem layer
- **Real Examples** - Actual frameworks, tools, and hardware platforms
- **Resource Links** - Direct links to official documentation
- **Educational** - Clear explanations and insights for each layer

## 🏗️ Architecture Layers

### Layer 1: High-Level Frameworks
**Developer Entry Points**
- 🔥 **PyTorch** (nn.Module)
- 🟠 **TensorFlow** (Graph/Eager)
- 🔵 **JAX** (NumPy-style)

### Layer 2: Bridges & Frontends
**Translation & Optimization**
- 📦 torch.compile, torch_xla, torch-mlir
- 📦 tf.function, TF-MLIR, TFLite Converter
- 📦 jax.jit, jax2onnx

### Layer 3: Intermediate Representations
**Universal Formats**
- 📋 **ONNX** - Universal exchange format
- 📦 **StableHLO** - OpenXLA intermediate representation
- 🏗️ **MLIR** - Multi-level IR infrastructure
- 📋 **FX Graph** - PyTorch internal representation

### Layer 4: Compilers & Runtimes
**Optimization Engines**
- 🔧 **TorchInductor** - PyTorch's graph compiler
- ⚡ **OpenXLA (XLA)** - Accelerated Linear Algebra
- 🎯 **TVM** - Tensor compilation stack
- 📦 **IREE** - Intermediate Representation Execution Environment
- ▶️ **ONNX Runtime**, **TensorRT**, **TFLite**

### Layer 5: Hardware Targets
**Execution Platforms**
- 💻 **CPUs** - General-purpose processors
- 🎮 **GPUs** - Graphics processing units
- 🧠 **TPUs** - Tensor processing units
- 📱 **Mobile NPUs** - Neural processing units
- 🍎 **Apple Neural Engine** - Apple's AI accelerator

## 🚀 Key Insights

### **Multiple Pathways**
Each framework offers multiple compilation paths to the same hardware, providing flexibility in optimization strategies and deployment scenarios.

### **ONNX as Universal Bridge**
ONNX serves as the critical interchange format, enabling models trained in one framework to run on runtimes optimized for different deployment scenarios.

### **Hardware Specialization**
Different deployment targets (mobile, server, edge) have specialized runtimes and optimization paths tailored to their specific constraints and capabilities.

### **Ecosystem Complexity**
The modern ML deployment landscape involves numerous intermediate steps and format conversions, reflecting the diversity of hardware targets and optimization requirements.

## 🎮 Usage

### **Website Navigation**
1. **Visit**: [https://hoyathalis.github.io/ML_Framework_Ecosystem_Flowchart/](https://hoyathalis.github.io/ML_Framework_Ecosystem_Flowchart/)
2. **Explore**: Use mouse wheel or touch gestures to zoom
3. **Navigate**: Click and drag to pan around the diagram
4. **Learn**: Read the detailed layer explanations below the chart

### **Interactive Controls**
- **Zoom In/Out**: Mouse wheel or `+`/`-` buttons
- **Pan**: Click and drag the diagram
- **Reset View**: Home button or `Ctrl/Cmd + 0`
- **Fullscreen**: Fullscreen button or `F11`
- **Theme Toggle**: Light/dark mode button in header

### **Keyboard Shortcuts**
- `Ctrl/Cmd + +` - Zoom in
- `Ctrl/Cmd + -` - Zoom out  
- `Ctrl/Cmd + 0` - Reset zoom
- `Escape` - Exit fullscreen mode

## 🛠️ Technical Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Diagram Engine**: [Mermaid.js](https://mermaid.js.org/) v10.6.1
- **Styling**: CSS Custom Properties, CSS Grid, Flexbox
- **Hosting**: GitHub Pages
- **Font**: [Inter](https://rsms.me/inter/) for optimal readability
- **Icons**: Unicode symbols for universal compatibility

## 📱 Browser Support

- ✅ **Chrome** 90+
- ✅ **Firefox** 88+
- ✅ **Safari** 14+
- ✅ **Edge** 90+
- ✅ **Mobile Browsers** (iOS Safari, Chrome Mobile)

## 🤝 Contributing

We welcome contributions to improve the accuracy and completeness of this diagram!

### **How to Contribute**
1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/improve-diagram`)
3. **Make** your changes to the diagram or documentation
4. **Test** your changes locally
5. **Commit** with clear messages (`git commit -m 'Add XYZ framework connection'`)
6. **Push** to your branch (`git push origin feature/improve-diagram`)
7. **Open** a Pull Request

### **What to Contribute**
- 🔄 **Update outdated connections** or framework information
- ➕ **Add missing frameworks** or tools
- 📝 **Improve documentation** and explanations
- 🐛 **Fix bugs** or rendering issues
- 🎨 **Enhance UI/UX** improvements
- 🌐 **Add translations** or internationalization

### **Guidelines**
- Verify information with official documentation
- Keep the diagram clean and readable
- Test on multiple devices and browsers
- Follow existing code style and patterns
- Include relevant links to official resources

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Framework Teams** - PyTorch, TensorFlow, JAX, and all the amazing ML framework developers
- **ONNX Community** - For creating the universal model format
- **Hardware Vendors** - NVIDIA, Google, Apple, and others pushing AI acceleration forward
- **Open Source Community** - For building the tools that make this ecosystem possible

## 📞 Support

- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/hoyathalis/ML_Framework_Ecosystem_Flowchart/issues)
- 💡 **Feature Requests**: [GitHub Issues](https://github.com/hoyathalis/ML_Framework_Ecosystem_Flowchart/issues)
- 📧 **Questions**: Open a [GitHub Discussion](https://github.com/hoyathalis/ML_Framework_Ecosystem_Flowchart/discussions)

---

<div align="center">

**[🌐 Visit Live Website](https://hoyathalis.github.io/ML_Framework_Ecosystem_Flowchart/)**

Made with ❤️ for the ML Community

</div>