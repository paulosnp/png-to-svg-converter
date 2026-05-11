# VectorStudio - PNG to SVG

VectorStudio is a fast, client-side web application that converts raster images (PNG/JPG) into high-quality, monochromatic Scalable Vector Graphics (SVG). 

It uses the powerful **Potrace** algorithm compiled to WebAssembly (Wasm) to trace mathematical paths and smooth curves directly in your browser, without any server-side processing.

## 🚀 Features
- **Instant Conversion:** Drag and drop images to vectorize them instantly.
- **Client-Side Only:** 100% privacy-friendly. Your images never leave your device.
- **Wasm Powered:** Utilizes `@cadit-app/potrace-ts` for extreme tracing performance and precision.
- **Responsive Output:** Automatically injects an adaptive `viewBox` so your generated SVGs are infinitely scalable.
- **Premium UI:** Glassmorphism aesthetics, dark mode, smooth transitions, and drag-and-drop feedback.

## 🛠️ How to use
You can access the app directly via GitHub Pages (once deployed).
Alternatively, simply clone this repository and open the `index.html` file in your favorite browser! No `npm install` or local server required.

1. Drag and drop a PNG or JPG file into the "Imagem Original" zone.
2. Wait a few milliseconds while the Wasm algorithm processes the traces.
3. Click **Baixar SVG** to save your new vector file.

## 💻 Built With
- **HTML5 & Vanilla CSS** for a dependency-free, lightning-fast UI.
- **ES Modules & WebAssembly** for browser-native logic.
- **Potrace-ts** ([esm.sh/@cadit-app/potrace-ts](https://esm.sh/@cadit-app/potrace-ts)) for the tracing algorithm.

## 📝 License
This project relies on Potrace, which is licensed under the GPL-2.0 License. As such, any derivative works may also be subject to GPL-2.0.
