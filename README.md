# stabilo-onhw-recognition

Original Dataset: https://stabilodigital.com/onhw-dataset/

Experiments with character recognition model for timeseries dataset.

Several writers wrote different letters with special pen.
For each sample data from following sensors was obtained:
  * 2 Accelerometers
  * Gyroscope
  * Magnetometer
  * Force sensor
 
This data was processed by TSFEL and TSFresh libraries.
Different models were trained using original data and processed.
Best model is LightGBM using resampled data.
