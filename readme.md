### Run the notebook to predict the user's financial investment's loss or gain [Support and Resistance Strategy]

## Video solution of Finbro:
https://github.com/Amarnath-Rao/Finbro/assets/96937608/403cb9bc-c0cf-46ad-bf2c-1ec5c8ce5d58

## Notebook link: https://colab.research.google.com/drive/1QeELaqTgtRb5n1frtvWv_3nwCKkjdQlN?usp=sharing
### Problem it solves
Finbro aims to solve several key problems in the financial industry:
* Real-Time Decision Making: Traditional financial decision-making can be slow and inefficient. Our system uses the LLM open-source model to provide real-time notifications, enabling executives and sales personnel to make quick decisions based on current data.
* Predictive Analysis: Predicting financial loss is a complex task that requires analyzing numerous variables. Our system uses machine learning to predict potential financial losses based on historical data, helping users to mitigate risk.
* Future Investment Value Prediction: Predicting future investment values can help users plan their financial strategies more effectively. Our system uses LSTM, a type of recurrent neural network, to predict next month’s investment values based on past trends.
* Automated Alerts: Keeping track of significant transactions or investments can be challenging. Our system sends out notifications when these hit crucial points, allowing users to take immediate action.
Overall, Finbro makes financial decision-making more efficient, informed, and proactive, which can lead to improved financial outcomes. It’s a great example of how technology can transform traditional industries.

### Challenges we ran into
* Paid API: OpenAI APIs can be costly and time-consuming, especially when dealing with financial data. However, we managed to work around this by optimizing your usage and ensuring that every API call was necessary and provided valuable information.
* Limited Data: Machine learning models perform better with more data, but have a limited dataset to work with. Despite this, we were able to train your model effectively, demonstrating the robustness of your approach.
* Data Inconsistency: Backtracking new data with previous data can indeed lead to inconsistencies. However, we addressed this by implementing rigorous data cleaning and preprocessing steps, ensuring that your ML model received high-quality, consistent data.

#### -> We utilized MongoDB and Flask for our backend to ensure that user responses are stored, allowing the model to yield improved results over time. Furthermore, we’ve incorporated an option in the interface that allows users to choose whether or not they want their data saved.

### Core Techs Used:
* Generative AI
* Python
* Machine Learning
* Deep Learning
* Data science
* MongoDB
* Flask

## For decision-making in financial analyses, 

![image](https://github.com/Amarnath-Rao/Finbro/assets/96937608/2c7a4ebd-1e92-41f6-911d-1777a00fac3d)
![image](https://github.com/Amarnath-Rao/Finbro/assets/96937608/59d26b66-765f-4214-8ca9-0f61fa8247c8)

extract & go to user-int-mistrail folder & run
### Linux & WSL2

```
curl https://ollama.ai/install.sh | sh
```

* you can also add multiple user data and train model, as per now single users financial growth and loss were taken into dataset
