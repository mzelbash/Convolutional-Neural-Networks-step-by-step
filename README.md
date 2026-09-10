# Convolutional Neural Networks, step by step

An interactive, single-page explainer that walks students through convolutional neural networks from the very first idea ("an image is just a grid of numbers") all the way to modern architectures like ResNet-50, U-Net, and a first look at attention.

**Live demo:** https://mzelbash.github.io/Convolutional-Neural-Networks-step-by-step/

Built for **SEAS-8525** by **Dr. Elbasheer**, George Washington University.

---

## What this is

A visual, hands-on companion to a CNN lecture series. Every core operation is something you can step through and watch: the filter slides, the numbers multiply and add, the feature map fills in, the map shrinks, the vector grows back into an image. The goal is intuition first, with the exact equations shown right next to each worked example.



## Highlights

- **21 chapters** arranged as a single story, navigable from a left-hand menu.
- **Step-through animations** for convolution, RGB channel summation, pooling, and transpose convolution, with the arithmetic shown term by term.
- **Live equations** (rendered with KaTeX) that recompute as you change stride, padding, filter size, and channel counts.
- **Worked real architectures:** AlexNet computed layer by layer, ResNet-50, and the U-Net encoder/decoder shape.
- **Interactive decision tools,** including a transfer-learning "which mode should I use?" picker.
- **Consistent color language** across every diagram: blue for input pixels, amber for filter weights, green for results.
- **No build step and no dependencies to install.** The whole thing is one self-contained HTML file.

## Chapters

**Foundations**
1. An image is numbers
2. The filter
3. Convolution: slide, multiply, add
4. Color images (RGB)
5. Stride and padding
6. Many filters
7. Pooling
8. Activation (ReLU)
9. Flatten and classify (softmax)
10. Why it works (receptive field and weight sharing)
11. The full pipeline
12. AlexNet, layer by layer

**Modern building blocks**
13. Transpose convolution
14. Skip connections
15. The 1x1 convolution
16. ResNet-50
17. U-Net
18. A first look at attention

**For your research**
19. Image datasets worth knowing
20. Transfer learning and fine-tuning
21. Questions students actually ask (FAQ)

## Running it

The app is a single HTML file, so there is nothing to build.

- **Online:** just visit the live demo link above.
- **Locally:** download the HTML file and open it in any modern browser (double-click is fine).
- **Serving it yourself:** drop the file into any static host. On GitHub Pages, name it `index.html` (or set it as the entry) and enable Pages for the repository.

An internet connection is needed the first time you open it, because the fonts and the math renderer load from a CDN.

## Built with

- Plain HTML, CSS, and vanilla JavaScript (no framework, no bundler).
- [KaTeX](https://katex.org/) for fast, crisp equation rendering.
- SVG and the Canvas API for the diagrams and animations.

 
## Feedback

Issues and suggestions are welcome. If something is unclear or you would like a chapter added, open an issue on this repository.
