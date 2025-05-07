# 📦 Text or Photo to 3D Model Generator

This project is a prototype that generates a simple 3D model from either:
- A **photo** of a single object (e.g., a chair, car, toy), or
- A **text prompt** (e.g., "a small toy car")

The generated 3D model is output in `.obj` format and can be visualized in 3D or used for 3D printing.

---

## ✨ Features

- 📷 **Image Input**: Removes background and processes the image to focus on the object.
- 📝 **Text Input**: Uses OpenAI’s SHAP-E model to generate a 3D shape from descriptive text.
- 🛠️ **3D Output**: Exports 3D models as `.obj` files.
- 🧾 **Visualization**: Provides a simple interactive 3D preview using Plotly.

---

## 🚀 How to Run

### 1. Clone and set up environment
```bash
git clone https://github.com/yourusername/text-photo-to-3d.git
cd text-photo-to-3d
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
