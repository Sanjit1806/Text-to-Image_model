# Image to Text Generation

Generating images from textual descriptions using 2 google pre-trained text embedding model.

## Project Structure

- **Models Folder**: Contains links to pre-trained models.
  - `smaller_model.txt`: Link to the smaller model, suitable for environments with limited computational resources.
  - `larger_model.txt`: Link to the larger model, ideal for environments with ample computational resources.
  
- **requirements.txt**: Lists all the dependencies required to run the project. Make sure to install these before running the code.

- **main.ipynb**: The main Jupyter notebook containing the code for the image-to-text generation model. This notebook demonstrates the entire pipeline from loading the model to generating text from input images.

## Installation

To get started with this project, follow the steps below:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Sanjit1806/Text-to-Image_model.git
    ```
  
2. **Navigate to the project directory**:
    ```bash
    cd Text-to-Image_model
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Download the model files**:
    - Larger model: [Download link](https://tfhub.dev/google/universal-sentence-encoder/4)
    - Smaller model: [Download link](https://tfhub.dev/google/nnlm-en-dim50/2)
    
## Usage

1. Open the `main.ipynb` notebook using Jupyter Notebook or Jupyter Lab.
2. Follow the instructions in the notebook to load the model, process images, and generate textual descriptions.
3. Experiment with different models based on your resource availability by loading either the smaller or larger model.

## Acknowledgments

This project utilizes 2 pre-trained models  for image-to-text generation.
- Google Universal Sentance Encoder trained with a deep averaging network (DAN) encoder (512-dim embedding vectors).
- Google Feed-Forward Neural-Net Language Models with pre-built OOV (128-dim embedding vectors).

