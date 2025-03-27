# Style Transfer Using VGG19

### Overview
This notebook implements Neural Style Transfer based on the method proposed by Gatys et al. using PyTorch and a pre-trained VGG19 model.

##### Content Image – Provides the structure (e.g., dog).
##### Style Image – Provides the artistic texture (e.g., Vassily_Kandinsky_Composition_7).
##### Output – A stylized image that blends the structure of the content with the texture of the style.

---

## 1. Setup Instructions

#### Requirements
Install the following:
- Python 3.x
- PyTorch
- torchvision
- matplotlib
- numpy
- PIL (Pillow)

Recommended: Run on GPU (locally or using Google Colab).

---

## 2. Running the Notebook

#### Steps
1. Open `Style_Transfer_Exercise.ipynb` in Jupyter or Colab.
2. Place your images inside the `images/` folder:
   - Example: `images/dog.jpg` (content)
   - Example: `images/starry_night.jpg` (style)
3. Update the paths in the notebook if needed.
4. Run all cells from top to bottom.

---

## 3. What It Does

- Loads and preprocesses the content and style images.
- Extracts features using a frozen VGG19 model.
- Computes content and style losses.
- Iteratively optimizes a target image to minimize loss.
- Displays:
  - Content vs Style vs Final Output
  - Loss curves over time (Total, Content, Style)

---

## 4. Customization Options

#### You Can Tune:
- `content_weight` and `style_weight`
- Style layer weights (`conv1_1` to `conv5_1`)
- Learning rate and number of iterations

`Python
- content_weight = 1
- style_weight = 1e2
- steps = 4000
- optimizer = optim.Adam([target], lr=0.005)

## Expected Outputs
- Image Filtering: Edge-detected images & bar chart.


- CNN Model: Architecture visualization, accuracy/loss curves, test results.

### Notes
- Ensure dependencies are installed.
- Modify file paths if needed.
- Recommended: Run in Jupyter Notebook or Google Colab for better visualization.

