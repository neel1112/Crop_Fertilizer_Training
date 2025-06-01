# Crop and Fertilizer Recommendation System

## Project Overview
This project leverages machine learning to provide intelligent recommendations for crop selection and fertilizer usage based on environmental and soil conditions. The system helps farmers make data-driven decisions to optimize agricultural productivity.

## Features

### 1. Crop Prediction
- Predicts the most suitable crop to grow based on environmental factors
- Considers parameters like temperature, humidity, pH level, and rainfall
- Uses machine learning models for accurate predictions

### 2. Fertilizer Recommendation
- Suggests the appropriate fertilizer based on soil composition and crop type
- Takes into account soil nutrients (Nitrogen, Phosphorus, Potassium)
- Considers environmental conditions and soil type

## Dataset

The project utilizes two main datasets:

1. **Crop Dataset** (`crop_dataset.csv`)
   - Contains information about various crops and their optimal growing conditions
   - Includes parameters like N, P, K levels, temperature, humidity, pH, and rainfall

2. **Fertilizer Dataset** (`fertilizer_dataset.csv`)
   - Contains soil and environmental data for fertilizer recommendations
   - Includes temperature, humidity, moisture, soil type, and crop type

## Technical Implementation

### Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Structure
- `Crop_Prediction.ipynb`: Jupyter notebook for crop prediction model
- `Fertilizer_recommendation.ipynb`: Jupyter notebook for fertilizer recommendation model
- `crop_dataset.csv`: Dataset for crop prediction
- `fertilizer_dataset.csv`: Dataset for fertilizer recommendation

## Usage

### Crop Prediction
1. Open `Crop_Prediction.ipynb` in Jupyter Notebook
2. Run all cells to train the model
3. Input your environmental parameters to get crop recommendations

### Fertilizer Recommendation
1. Open `Fertilizer_recommendation.ipynb` in Jupyter Notebook
2. Run all cells to train the model
3. Input soil and environmental parameters to get fertilizer recommendations

## Results

The models provide:
- Accurate crop predictions based on environmental conditions
- Personalized fertilizer recommendations for optimal crop growth
- Data visualization for better understanding of the relationships between different parameters

## Future Enhancements

- Integration with weather APIs for real-time data
- Mobile application for field use
- Support for more crop varieties and fertilizer types
- Integration with IoT devices for automated data collection

## License

This project is open source and available under the MIT License.

## Contact

For any queries or contributions, please open an issue in the repository.
