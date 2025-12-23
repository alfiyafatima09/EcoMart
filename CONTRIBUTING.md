# Contributing to Ecomart

We appreciate your interest in contributing to Ecomart, a Chrome extension designed to promote sustainable shopping. This guide will help you understand how you can contribute, set up the development environment, and adhere to best practices.

## 🛠️ Development Setup

### 1. **Clone the Repository**

```bash
git clone https://github.com/alfiyafatima09/EcoMart.git
cd EcoMart
```

### 2. **Install Dependencies**

Ensure you have Node.js installed (v14 or later). Then, run the following command to install dependencies:

```bash
npm install
```

### 3. **Build the Extension**

```bash
npm run build
```

### 4. **Load the Unpacked Extension in Chrome**

1. Open Chrome and navigate to [chrome://extensions](chrome://extensions).
2. Enable **Developer Mode**.
3. Click **Load Unpacked** and select the `build` folder.
4. The extension should now be loaded and ready for testing.

### 5. **Running the Development Server for the Website**

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

### 6. **Testing the Extension**

Visit any supported e-commerce platform, click the Ecomart extension icon, and verify that sustainability insights and eco-friendly alternatives are displayed.


## 🚀 How to Contribute

We welcome contributions from the community! Here's how you can get involved:

### **Reporting Issues**

If you encounter bugs or have feature requests, please [open an issue](https://github.com/alfiyafatima09/EcoMart/issues).

### **Feature Requests**

We’d love to hear your ideas! Open a feature request by submitting an issue.

### **Code Contributions**

Follow these steps to contribute code:

1. **Fork the Repository**

   Click the **Fork** button on the top right of the repository page.

2. **Create a New Branch**

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**

   Write clean, well-documented code and ensure all tests pass.

4. **Commit Changes**

   ```bash
   git commit -m "Add your meaningful commit message"
   ```

5. **Push to Your Branch**

   ```bash
   git push origin feature/your-feature-name
   ```

6. **Submit a Pull Request**

   Go to the original repository and click **New Pull Request**. Ensure you provide a clear description of the changes.


## 🧑‍💻 Code Style Guidelines

- Follow [JavaScript Standard Style](https://standardjs.com/).
- Use meaningful variable and function names.
- Ensure code is modular and well-commented.
- Write clean and maintainable code.

## 📚 Best Practices

- Write meaningful commit messages.
- Ensure the codebase remains consistent with the existing architecture.
- Avoid introducing unnecessary dependencies.


## 📸 Screenshots

Add relevant screenshots side by side using Markdown:

| Screenshot 1 | Screenshot 2 |
|-------------|--------------|
| [Original screenshot before change] | [Screenshot after changes made] |


