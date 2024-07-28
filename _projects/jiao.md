---
authors: ["Bill Jiao"]
title: Predicting Machine Failures in Toothbrush Tufting Machines based on Temperature, Shock, and Vibrations Data
paper_url: /static_files/projects/jiao_pred_maint.pdf
video_url: "https://mymedia.bu.edu/media/t/1_1jwbwzcy"
slides_url: /static_files/projects/jiao_pred_maint_preso.pdf
tags: ["Time Series Analysis", "RNN", "LSTM"]
---

This project proposes a machine-learning method to optimize dental industry manufacturing systems, specifically for toothbrush tufting machines. The project optimized
a Long Short-Term Memory Model to generate machine states predictions based on vibrations, shock, and temperature data. To achieve improved performance, the project
adjusted learning rates, training strategies, training loss functions (and weights). The
model achieved a loss value of 1.1462 on the regular cross entropy loss function and a
loss value of 0.1629 on the binary cross entropy function. On the testing set, the cross
entropy loss trained model achieved a macro F1 score of 0.3342, a micro F1 score of
0.9081, and a weighted F1 score of 0.9383. This means that the model does a good job
creating general predictions and correctly identifies normal operating states. However,
the model does not do as well at failure state predictions.
