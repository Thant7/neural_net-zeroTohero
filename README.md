Implementation of Anderj Karpathy's neural network series.


Bigram and Trigam
    You can see that the probabilistic sampling and neural network sampling should be the same because the matrix N is supposedly equal to the weight matrix W.

MLP (3rd video on the series)
    Basically reimplemented the code from the paper called "A neural Probabilistic Language Model" by Bengio et al. Although in this paper, each word is a token but in my code, I have changed to characters and they are flexible. 

  Paper summary ----> proposed a newthod to train langugae models by representing words as continuous distribution (vectors) and letting the network learn how to represent them. What was known from before the release of this paper was to use the probability of sequence of words ( which is easily broken down into predicting the next word given the previous word).
  
  ![image](https://github.com/user-attachments/assets/1fbb39e9-882e-4478-bbfc-5f1ad99444d0)
  
 
