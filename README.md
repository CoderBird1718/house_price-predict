#  House Price Prediction App

A machine learning web application built with Python and Streamlit that predicts house prices based on various features like area, bedrooms, bathrooms, and amenities.

##  Features

- Interactive web interface for easy data input
- Real-time house price predictions
- Support for multiple house features:
  - Area (square feet)
  - Number of bedrooms and bathrooms
  - Stories
  - Amenities (main road access, guest room, basement, etc.)
  - Furnishing status
  - Parking spaces
- Clean and user-friendly UI
- Input validation and error handling

## 🛠️ Technologies Used

- **Python 3.x**
- **Streamlit** - Web application framework
- **Joblib** - Model serialization
- **Pandas** - Data manipulation
- **Scikit-learn** - Machine learning (model training)

##  Requirements

Create a `requirements.txt` file with the following dependencies:

- streamlit= 1.31.0
- joblib = 1.3.2
- pandas = 2.1.4
- scikit-learn = 1.4.0
- numpy = 1.26.3

##  Project Structure

house-price-prediction/
│
├── app.py                      # Main Streamlit application
├── house_price_model.pkl       # Trained machine learning model
├── model_columns.pkl           # Feature columns used in training
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation

##  Features Explained

### Input Features:
- **Area**: Total area of the house in square feet
- **Bedrooms**: Number of bedrooms (1-5)
- **Bathrooms**: Number of bathrooms (1-4)
- **Stories**: Number of floors (1-4)
- **Main Road**: Whether the house has main road access
- **Guest Room**: Availability of a guest room
- **Basement**: Presence of a basement
- **Hot Water Heating**: Hot water heating system availability
- **Air Conditioning**: Air conditioning availability
- **Parking**: Number of parking spaces (0-3)
- **Preferred Area**: Whether the house is in a preferred area
- **Furnishing Status**: Furnished, semi-furnished, or unfurnished

##  Sample Prediction

Example input:
- Area: 2500 sq.ft
- Bedrooms: 3
- Bathrooms: 2
- Stories: 2
- All amenities: Yes
- Furnishing: Semi-furnished
- Parking: 2

Output: Estimated House Price: ₹ XX,XX,XXX.XX
