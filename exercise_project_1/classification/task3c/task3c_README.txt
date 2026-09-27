There are many options to try here for OUTLIERS:

- IQR
- z-score
- Isolation Forest
- Elliptic Envelope (very good at finding outliers WITHIN the data distributions)

Basic tool to detect NOISE is to use MAD.

Furthermore, you can use seaborn visuals to detect if there are any noisy variables in the dataset.

Noise can also imply dataset-wise noise and/or column-wise noise.
Noise can be systematic, or it can be due to faulty measurements/sensor glitches.
Also impossible values and random errors are considered noise. 
Noise can also be typos in the data.

Elliptic Envelope can be useful for finding weird combinations of data within the dataset (~noise).

Feel free to consult your favorite AI for other noise types and strategies to detect them!