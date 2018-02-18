# Predict Machine Failure

Can you identify indications of a potentional machine failure with enough time to do something before the failure occurs? 

tldr: Maybe. But it's not going to be using this method.

- [**Load Data:**](https://github.com/CurtLH/predict_machine_failure/blob/master/1_load_data.ipynb)
Loading provided CSV files into a Postgres database.
- [**Inspect Data:**](https://github.com/CurtLH/predict_machine_failure/blob/master/2_inspect_data.ipynb)
Explore datasets to better understand how the machine produces data.
- [**Prepare Data:**](https://github.com/CurtLH/predict_machine_failure/blob/master/3_prepare_data.ipynb)
Aggregrate dataset from 2-minute intervals into 1-hour intervals and create an indicator of failure within the next hour.
- [**Predict Failure:**](https://github.com/CurtLH/predict_machine_failure/blob/master/4_predict_failure.ipynb)
Predict whether or not the machine is going to fail within the next hour.
- [**Predict Downtime:**](https://github.com/CurtLH/predict_machine_failure/blob/master/5_predict_downtime.ipynb)
Predict whether or not the machine is going to go down for any reason (maintance, failure, etc.) within the next hour.
- [**Predict Time Until Downtime:**](https://github.com/CurtLH/predict_machine_failure/blob/master/6_predict_time_until_down.ipynb)
Predict the amount of time until the machine next goes down for any reason (maintenance, failure, etc.).
