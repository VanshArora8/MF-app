# 🎈 Machine Predictive Maintenance

Predictive maintenance has emerged as a vital strategy in industrial systems to reduce 
unexpected equipment failures, minimize downtime, and optimize maintenance schedules. 
This project presents a machine predictive maintenance solution leveraging supervised 
machine learning algorithms to forecast potential failures based on historical sensor data. Using 
a labeled dataset comprising features such as torque, temperature, pressure, and usage cycles, 
several supervised classification models—including Random Forest, Support Vector Machine 
(SVM), and Logistic Regression—were trained and evaluated. The Random Forest model 
delivered the highest accuracy and robustness, making it the final choice for deployment. 
To enhance accessibility and user interaction, a graphical user interface (GUI) was developed 
using Streamlit, an open-source Python framework for building data-driven web applications. 
The GUI allows users to upload new data in real time, view predictive results, and visualize 
critical metrics such as feature importance, prediction probability, and maintenance trends. This 
interface also supports basic preprocessing options, enabling end users with minimal technical 
background to interact with the predictive system efficiently. 
By integrating machine learning with an intuitive web-based GUI, the project demonstrates a 
scalable and user-friendly approach to predictive maintenance. The system not only aids in 
early detection of potential failures but also empowers maintenance teams with actionable 
insights, contributing to smarter and more cost-effective operations. The modularity of the 
system also ensures adaptability across different types of machinery and industrial contexts. 

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://blank-app-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
