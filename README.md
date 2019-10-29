# calibration-using-DNN
There are various approaches to tackle the problem of calibrating traffic assignment models, such as manual calibration and optimization algorithms. The calibration process is a time-consuming task and it has to be repeated for each model on its own. Using machine learning, this repo provides a generic model that could be used to calibrate different models (built in Aimsun) faster than all other approaches.

Training and testing datasets are generated using metro package available at:
https://github.com/taha-islam/metro/blob/master/aimsun/calibration_data_gen.py
