# 🧠 Text Generation using LSTM

## Overview  
This project demonstrates how to generate text using a character-level **LSTM (Long Short-Term Memory)** network. It is designed to showcase how deep learning can be used to predict and generate text sequences based on a learned context, capturing the sequential structure of a dataset.

The model is trained on a text corpus and uses the learned character dependencies to generate coherent text fragments character by character.

## Reference  
The project is inspired by standard text generation techniques using RNNs and LSTMs as seen in various deep learning courses and tutorials. It follows practices outlined in the TensorFlow documentation and deep learning literature.

## Key Highlights  
- **Character-Level Tokenization**: The dataset is split into overlapping sequences of characters, and each character is converted into a numeric representation.
- **LSTM-Based Neural Network**: A deep LSTM network is constructed to learn long-term dependencies and patterns within the text.
- **Text Generation**: Once trained, the model is able to generate creative text sequences based on a given seed input.

## Dataset  
The training data is a raw text corpus that can be replaced with any `.txt` file containing natural language content. The notebook processes this text to train the LSTM model.

> 📌 You can customize the dataset by replacing the `path_to_file` with any `.txt` file of your choice.

## Requirements  
- Python 3.x  
- Libraries:
  - TensorFlow
  - NumPy
  - Matplotlib

You can install the required libraries using:
```bash
pip install tensorflow numpy matplotlib
```

## File Structure  
- `Day18 LSTM for text generation.ipynb` — Jupyter notebook containing all the code, from data preprocessing to text generation.

## Output  
The model will generate sequences of text based on a provided seed string and learned character relationships. You can adjust parameters like temperature to control the creativity of the generated output.

## License  
This project is open-source and available under the [MIT License](LICENSE).

## Contributing  
Contributions and suggestions are welcome! Feel free to fork this repo and submit a pull request.
