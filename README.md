# cos424-a3
Things to try by Thursday:
For Related work stuff, just dump the link under the method it relates to.

1) Multiplicative weights (Sid)
  - Theorhetical awesomeness = Theorhetical bounds that suggest that this is always a great idea (always competitive).
  - Paper:

2) Collaborative Filtering (with sparsity enhancements) (Abhi)
  - Netflix Recommendation Challenge / CF is popular as a recommendation algorithm.
  - Modified to handle sparsity via paper: http://delivery.acm.org/10.1145/1730000/1722966/p4-su.pdf?ip=140.180.252.179&id=1722966&acc=PUBLIC&key=7777116298C9657D%2ECCADDB884D0A3BC7%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&CFID=767357552&CFTOKEN=25028195&__acm__=1459724094_b2bd567bd0a23703a8825b0f9a184a7b
  - More modifications to CF: http://www.mimuw.edu.pl/~paterek/ap_kdd.pdf

3) Hidden Markov Model (Sid)
  - HMM because its simple and encodes latent structure. We are making the assumption that the data is not missing at random, but instead has some latent structure to it.
  - Provides a least effort baseline

4) Neural Network  (If time left, Abhi)
  - Multi layered perceptrons remove noise from vectors for image denoising. We figured that we can try denoising our vector and use the denoising processes as a process for prediction
  - Binarized input to the NN = output the new binary vector representing connections
  - Imputed vector for missing values = injected into the NN, output represents denoised vector
