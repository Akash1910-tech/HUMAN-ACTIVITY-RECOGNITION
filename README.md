# HUMAN-ACTIVITY-RECOGNITION
 Human Activity Recognition (HAR) is the process of automatically identifying physical activities performed by a person using data collected from sensors such as accelerometers, gyroscopes, or cameras. It plays a crucial role in applications like fitness tracking, healthcare monitoring, smart homes, and human-computer interaction. 
  HAR systems typically use machine learning or deep learning models to classify activities such as walking, running, sitting, standing, or jumping based on patterns in the collected data.
# Human Activity Recognition (HAR) using Time Series Data

This project focuses on Human Activity Recognition (HAR) using time series data collected from motion sensors like accelerometers and gyroscopes. The goal is to classify different physical activities (e.g., walking, sitting, running) based on patterns in sensor readings.

## 📁 Dataset Description

The dataset consists of multivariate time series data collected from wearable sensors (e.g., smartphones or smartwatches). Each sample represents a short time window of sensor readings and is labeled with a specific activity.

### Common Sensors:
- Accelerometer (X, Y, Z axes)
- Gyroscope (X, Y, Z axes)

### Example Activities:
- Walking
- Sitting
- Standing
- Lying Down
- Walking Upstairs
- Walking Downstairs

### File Structure (Example):

## 📊 Data Format

- Each row in `X_train.txt` / `X_test.txt` is a flattened time window (e.g., 128 time steps × 9 features).
- Each row in `y_train.txt` / `y_test.txt` is the corresponding activity label.
- The data is pre-segmented into fixed-size windows.

## 🧠 Model Overview

This project uses deep learning models like LSTM, CNN, or hybrid CNN-LSTM architectures to classify human activities based on time series input.

## ⚙️ Dependencies

- Python 3.x
- NumPy
- Pandas
- TensorFlow / PyTorch
- Scikit-learn
- Matplotlib / Seaborn

Install the requirements with:

```bash
pip install -r requirements.txt

## How to Run
1.Clone the repository:

git clone https://github.com/your-username/har-time-series.git
cd har-time-series
2.Prepare the dataset:

Download and place the dataset in the /data folder

3.Train the model

python train.py

4.Evaluate on test data:

python evaluate.py


Let me know if you're using a specific dataset (e.g., UCI HAR, WISDM, PAMAP2), and I can tailor this README further.

