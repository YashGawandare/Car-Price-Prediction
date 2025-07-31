# 🚗 Car Price Predictor with Gradio UI

This project predicts the **resale price of a used car** based on various attributes like showroom price, fuel type, kms driven, transmission type, etc. It uses a pre-trained machine learning model and presents a user-friendly interface via **Gradio**.

---

## 📌 Features

- Predicts car selling price based on key inputs.
- Interactive Gradio-based UI with enhanced color theme.
- Real-time predictions powered by a trained regression model.
- Runs smoothly in Google Colab or locally.

---

## 🧠 Tech Stack

| Technology     | Purpose                         |
|----------------|---------------------------------|
| Python         | Programming language            |
| scikit-learn   | ML model training and prediction|
| joblib         | Model serialization             |
| Gradio         | Web UI for predictions          |
| Google Colab   | Cloud-based execution           |

---

## 📊 Input Parameters

- **Showroom Price (₹)** — Original price of the car.
- **KMs Driven** — Total distance the car has traveled.
- **Fuel Type** — Petrol, Diesel or CNG.
- **Seller Type** — Dealer or Individual.
- **Transmission** — Manual or Automatic.
- **Previous Owners** — Number of owners before.
- **Car Age** — Age of the car in years.

---

## 🚀 Getting Started

### 🔗 Run in Google Colab

1. Upload your `car_price_model.pkl` file.
2. Open the notebook or copy this code into a Colab cell.
3. Install Gradio:  
   ```python
   !pip install gradio --quiet
