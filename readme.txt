Podosome Segmentation Code

--------------------------------------------------
1. Contents
--------------------------------------------------

- readme.txt
  This file. Instructions for setup and usage.

- podosome-segmentation.ipynb
  Jupyter/Colab notebook for demonstration of segmentation

- models.py
  Definition of segmentation model

- weight.pt
  Trained weights of segmentation model

- data/imgs.tif
  Example images for demonstration and testing purposes.

--------------------------------------------------
2. System Requirements
--------------------------------------------------

Tested environment::
- Google Colab (Python 3.12.12)
- PyTorch version 2.9.0

Required Python packages:
- torch
- matplotlib
- numpy
- tifffile

Hardware:
- GPU is recommended for faster execution,
  but CPU-only execution is also possible.

--------------------------------------------------
3. Installation
--------------------------------------------------

To run the notebook in Google Colab:
Upload the entire "podosome-segmentation" folder to your Google Drive under the "Colab Notebooks" directory.

Installation time: < 10 seconds on Google Colab (required packages are automatically installed upon notebook execution)

--------------------------------------------------
4. Demo and Running the Code
--------------------------------------------------

1. Open the notebook file (podosome-segmentation.ipynb).

2. Run all cells in the notebook sequentially.


The notebook produces:
- Segmentation mask saved as a TIFF file in the "results" directory
- Visualization of segmentation result

--------------------------------------------------
5. Expected Runtime
--------------------------------------------------

- Approximately 10 seconds for the demo data on Google Colab with GPU

--------------------------------------------------
6. Using the Code with Your Own Data
--------------------------------------------------

To apply the method to custom data:
1. Replace the example images in data with your own podosome images.

2. Update the input path in the notebook.

3. Run all cells.


--------------------------------------------------
7. License
--------------------------------------------------

The code and trained weights are released under the GNU General Public License v3.0.