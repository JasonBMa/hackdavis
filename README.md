# Hackdavis Project

Problem Statement: The Aggie Reuse Store currently has no way of monitoring the store's foot traffic, so they do not know how many students come in every week, when the students tend to come in, and what days of the week are most popular. Operating hours change from quarter to quarter, so they want to use customer traffic data to know when the most optimal time to open is and how to better staff their volunteers to support rush hour.

- Forecasting/Predictions
- Hardware: Arduino wired to a ultrasonic sensor -> imitate motion sensor
- Front-End
- Visualization

File Description:
- forecast.py: Python file that forecast based on the data from Day_m.csv model, built with LSTM Neural Network technique and python.
- Day_m.csv: Data mapped from Monthly_Milk_Production.csv containing columns of Day and Footprint of that Day in the week.
- Monthly_Milk_Production.csv: Cyclic Data that present a seasonal trend; used to mimik the footprints of the Used Store
