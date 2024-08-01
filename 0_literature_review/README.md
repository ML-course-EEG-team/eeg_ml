# Literature Review

## Preprocessing

The preprocessing stage involves transforming EEG signals into a suitable format for deep learning models, following methodologies from recent research.

### Techniques Used

- **Channel Selection**: Limiting to 17 movement-associated channels as described by Yimin Hou et al. (2020).
- **Bandpass Filtering**: Applying bandpass filters to isolate relevant frequency bands, also based on Yimin Hou et al. (2020).
- **Wavelet Transformation**: Using Morlet wavelet transformation for enhanced time-frequency analysis as per Yimin Hou et al. (2020).

### Paper References

- **Yimin Hou et al. (2020)**: Enhanced preprocessing techniques to improve EEG classification.
  
## Model Architectures

The project explores several deep learning architectures, focusing on CNNs for EEG classification.

### CNN Implementation

- **References**:
  - **A. Schirrmeister et al. (2017)**: Detailed exploration of CNNs for EEG decoding.
  - **Yann LeCun et al. (2015)**: Foundational paper on deep learning, emphasizing CNNs.

### Other Models

- **LSTM**: Discussed by Alaa M. M. Anwar et al. (2018) for temporal data handling.
- **RNN**: Explored by Rajesh Kumar et al. (2018) for modeling temporal dependencies.
- **DBN**: Highlighted by Wei Yang et al. (2015) for feature extraction, with further insights from Kun-Hsing Yu et al. (2018) on AI applications in healthcare.

## Methods

1. **Preprocessing**: Implemented in `preprocess_data.py`, focusing on data transformation.
2. **Model Training**: CNN model defined and trained in `train_model.py`, employing TensorFlow and Keras libraries.

## Outcomes

- **Accuracy Improvement**: The CNN model achieved significant accuracy improvements, aligning with findings in referenced papers.
- **Model Robustness**: Demonstrated robustness in classifying complex EEG patterns using deep learning techniques.

## Relation to Project

The project leverages techniques and findings from seminal papers in EEG signal processing and deep learning, incorporating their insights into both preprocessing and model development.

