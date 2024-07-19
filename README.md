KNU-ON
===============================
The 2nd Anomalous Diffusion (AnDi) challenge

Participated in the 2nd AnDi challenge as a KNU-ON team.
<hr>

Taegeun Song(1), Seunghee Han(1), Jaehyun Jeong(1), and Jihye Kim(1)

(1) Department of Data Information and Physics, Kongju National University, Korea

Deep-learning model: 1D CNN + BiLSTM + Self-Attention + MLP

Our Method is Additive features. The Additive features is method that to make input data of the deep-learning model.
We consider 8 features (mean and standard deviation of the position and speed, diffusion constant, displacement, speed change that max-speed minus min-speed and velocity autocorrelation with a leg time of 1). To predict diffusion coefficient and diffusion exponent we employed the deep-learning model and we calculated sum of features every 10 points from the trajectories as the input data of deep-learning model. But, when we predict diffusion coefficient, we only consider two features (mean of speed and diffusion constant). As a results, using deep-learning models, we predicted diffusion coefficient and diffusion exponent. Using predicted diffusion coefficient and diffusion exponent, we performed the 2nd AnDi challenge Track 2 - Single Traj Task.
