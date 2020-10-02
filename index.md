## Summary

<img src="img/infographic.png"/>

## Introduction & Background
This problem is a current [Kaggle competition](https://www.kaggle.com/c/hashcode-drone-delivery/overview) at time of attempting this project. 


## Methods

### Q-Learning
We expect to first use Q-Learning to solve the problem through reinforcement learning. In this case, the drones are our agents, and the actions are listed in the [Kaggle instructions](https://www.kaggle.com/c/hashcode-drone-delivery/data?select=hashcode_delivery_instructions.pdf). We intend to reward states that have products closer to customers. This would mean a drone carrying a load to a warehouse closer to a customer would increase the reward, and of course, delivering a product to a customer would increase reward further. There are cases where a drone should not only be completing a delivery in every flight. For example, a drone could pick up a side product, drop it off to another warehouse on the way to its main customer, then return to that closer warehouse later and pick up all the product necessary for this second order. 

### Graphical Neural Network (GNN)
Our stretch goal is to use a Graphical Neural Network (GNN), an uncommon approach. This implementation will be very difficult, which is why we left it as a stretch goal, however, we believe it is an extremely interesting and novel approach to the problem that may produce better results than typical approaches.

## Results



## Discussion



## References
[1] Scarselli, F., Gori, M., Tsoi, A. C., Hagenbuchner, M., & Monfardini, G. (2008). The graph neural network model. _IEEE Transactions on Neural Networks_, 20(1), 61-80.


