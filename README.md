# Renew_Power
My work description @RenewPower

Utilizing AI technology stack and ML algorithms for
  1. Rainfall prediction using radar & satellite images across Delhi region.
  2. Electricity demand forecasting for Government Of India bodies.
  3. System Application for ML modelling.
  4. IEX price forecasting and fraud detection across the energy ecosystem.




1. **Research**- Rainfall prediction using radar images over Delhi region, during monsoon season (accuracy margin > 95%). Use case- rainfall forecast data from 3rd party sources is highly inaccurate in monsoon season, causing high MAPE in electricity demand forecasting.

Challenges- Highly sparse data, textual noise in images, unpredictable cloud movement and reflectivity.
Solutions-  1. Domain expertise and EDA to cluster similar weather conditions
	    2. Keras OCR pipelines to remove textual noise
	    3. Prediction using attention LSTM
	    4. Use of GANs to improve output resolutions for further use

2. **Predictive analytics**- intraday, day ahead, week ahead, year ahead forecasting using NNs, RNN, ARIMA, Boosting, transfer learning (modelling time margin < 15 sec, data size > 2 GBs, mape< 1.5 for intraday and day ahead); Clients- BRPL, BYPL, CSPTCL, PSPCL.

Challenges- During uncertain weather conditions(sudden rainfall, fluctuating temperature), inaccurate weather forecast data is prevalent causing models to fail  
Solutions- 1. refine weather forecast using deep learning- rainfall prediction using radar images via frame prediction (LSTMs)
	   2. Using similarity based techniques(dynamic time warping), fuzzy logics, domain expertise to tune the models

3. **Windows system application for modelling** (8-10 NN based complex models for 120 different areas to be run simultaneously every 15 min.; each data size >2 GBs); Clients- JKSPDC, General Electric 

Challenges- Computational complexity very high causing system failure. Cloud systems and GPUs were prohibited.
Solutions- Using generators, parallel processing, EDA and domain expertise, anomalies and regularities separated to forecast better.


