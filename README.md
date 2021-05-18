# altitude_TSS_converter
A converter for Training Stress Score taking into account the altitude of your training activity and the altitude you live at.

Must have an accurate threshold power, average elevation of activity, and living altitude.
This code assumes an altitude factor of 1% per 500' altitude, as this has been cited as a good population estimate. 
If you know your specific conversion use that instead.

TSS is calculated based on your threshold power as the amount of metabolic stress from training. 
When you ascend to a higher altitude, your maximal capacity and threshold power are reduced. 
Thus, a re-calibration of the relative stress of the work done is useful.
