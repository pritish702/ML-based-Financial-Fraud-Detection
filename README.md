<h1>ML-based-Financial-Fraud-Detection</h1>
<h2>Introduction: </h2>

<p>
Financial fraud is a prevalent issue that plagues various industries, resulting in substantial financial losses and undermining consumer trust. The advent of Internet of Things (IoT) technology and the proliferation of interconnected devices along with growth in digital transactions have opened new avenues for fraudulent activities, necessitating innovative solutions to combat this emerging threat. This project aims to address this critical challenge by leveraging the power of IoT data and advanced machine learning techniques. 
</p>

<h3>Problem Statement:</h3>
<p>
Financial fraud can manifest in various forms, such as identity theft, credit card fraud, 
money laundering, and cybercrime. The challenge lies in effectively analyzing the massive 
volumes of data generated by IoT devices to uncover potentially fraudulent activities 
amidst legitimate transactions. Traditional rule-based systems struggle to keep pace with 
the ever-evolving tactics employed by fraudsters, necessitating the development of 
intelligent, adaptive, and scalable solutions.
</p>

<h3>Technical Gaps in Existing Solutions:</h3>
<p>
While there have been efforts to address financial fraud using machine learning 
techniques, existing solutions often fail to effectively integrate IoT data into the fraud 
detection process. Many traditional approaches rely solely on structured data from 
financial transactions, overlooking the valuable insights that can be gleaned from the rich 
contextual information provided by IoT devices. Additionally, existing solutions may 
struggle to handle the velocity, variety, and volume of data generated by IoT ecosystems, 
limiting their effectiveness in real-time fraud detection scenarios.
</p>

<h3>Dateset:</h3>
<p>
  The dataset used for this project is a synthetic dataset generated using the simulator 
called PaySim. PaySim uses aggregated data from the private dataset to generate a 
synthetic dataset that resembles the normal operation of transactions and injects 
malicious behavior to later evaluate the performance of fraud detection methods. 
PaySim simulates mobile money transactions based on a sample of real transactions 
extracted from one month of financial logs from a mobile money service implemented in 
an African country. The original logs were provided by a multinational company, who is a
provider of mobile financial services which is currently running in more than 14 countries 
all around the world.
This synthetic dataset is scaled down 1/4 of the original dataset. This dataset has more 
than 6 million records and 11 features per record.
</p>
Source: https://www.kaggle.com/datasets/ealaxi/paysim1

<h3>Results:</h3>
<p>
  Comparison of the performance of different machine learning algorithms on the basis of accuracy and F1 score:
</p>

![Screenshot 2024-08-09 215033](https://github.com/user-attachments/assets/de565821-46d5-4433-990a-0549e0da684e)
