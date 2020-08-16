# Machine-Sound-Classification
Sound classification using more data types
My work as a vibration analyst affords me the opportunity to hear many different machine sounds and to record those sounds and then to analyze those sounds using FFT and Waveform graphs as well as overall energy trends. What I have found is that the models are trained in ways we are not but still use many of the same tools. We use a Hanning window, we use FFT as well as waveform but we use both the FFT and the waveform to make calls. The current models use FFT converted through a Mel filterbank so the ML gets to use only one data set to perform a classification measured against a human, whereas we get to use both the FFT, and waveform, and overall trend to make our calls. The ML is being tasked to do more with much less. I will attempt to see if it is possible to level the playing field a bit by using either one model trained on multiple datasets or multiple models trained on separate datasets.


Most of my equipment runs at 1780rpm 4-pole speed or 3560 2-pole speed.
1780rpm / 60 = 29.6667rps 1 / 29.667 = 33.7ms/rev or 34ms/rev
3560 would eqaual 1/2 of the 1780 calc or 17ms/rev
btw, 90% of the equipment is running ok so I will train the model on a similar diet of sound files 90% good machines and 10% bad machines.

![](pics/360.rbm_AHU_EF135%20%20EXHAUST%20FAN_AV%20-%20O.D.E.%20VERT_7-21-2020%204-22-43%20PM%20Bearing%20Fault%2066.png)

