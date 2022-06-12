</heading1>Stochastic Gradient Descent
</p>
</p>Gradient Descent: It is an algorithm through which we increase efficiency of training of a neural 
network on a dataset. In this algorithm, aim is to minimize the "cost function". The cost function 
is the sum of squares of error in our result. To minimise the cost function, we move in the direction
of negative gradient of the cost function in each iteration to get to the minimum. The weights and biases
are adjusted accordingly at each iteration. How big the steps are gradient descent takes into the direction 
of the local minimum are determined by the learning rate, which figures out how fast or slow we will move 
towards the optimal weights. How big the steps are gradient descent takes into the direction of the local
minimum are determined by the learning rate, which figures out how fast or slow we will move towards the 
optimal weights. In Gradient Descent, "Batch” denotes the total number of samples from a dataset that is 
used for calculating the gradient for each iteration. In typical Gradient Descent optimization the batch 
is taken to be the whole dataset. Although, using the whole dataset is really useful for getting to the 
minima in a less noisy and less random manner, but this method becomes computationally expensive for huge
datasets. This problem is solved by Stochastic Gradient Descent.</p>
More about the cost function-></p>
A cost function is used to measure how well the model is finding a relation between the input and output. While accuracy functions tell you how well the model is performing, they do not provide you with an insight on how to better improve them. Hence, you need a correctional function that can help you compute when the model is the most accurate, as you need to hit that small spot between an undertrained model and an overtrained model.</p> 
For a linear regression –</p>
                                             Cost function= $\frac{sum_{i=0}^{n}{(h(x^{i})-y^{i})^{2}}}{n}$</p>
Where $h(x^{i})$ =observed value and $y^{i}$ =predicted value</p>
                                             Gradient descent $\theta = \theta-\alpha \frac{\partial x}{\partial y}$</p>
Where $\alpha$ = learning rate</p>
It decides how fast you move down the slope. If alpha is large, you take big steps, and if it is small; you take small steps. If alpha is too large, you can entirely miss the least error point and our results will not be accurate. If it is too small it will take too long to optimize the model and you will also waste computational power. Hence you need to choose an optimal value of alpha.
</p></p>

Stochastic Gradient Descent: In SGD, it uses only a single sample, i.e., a batch size of one,instead of 
the whole dataset to perform each iteration. The word ‘stochastic‘ means a system or a process that is 
linked with a random probability. Hence, in Stochastic Gradient Descent, a few samples are selected randomly
instead of the whole data set for each iteration. As the sample is randomly chosen, the path taken to reach 
minimum in SGD is generally nosier than typical Gradient Descent algorithm. But it doesn't matter much as we 
still reach minimum and in shorter time. Also, it usually takes a higher number of iterations to reach the minima, 
because of its randomness in its descent. Despite this, SGD is still computationally much less expensive than 
typical Gradient Descent. Hence, in most scenarios, SGD is preferred over Batch Gradient Descent for optimizing 
a learning algorithm.</p>
There is a downside of the Stochastic nature of SGD i.e once it reaches close to the minimum value then it doesn’t settle down, instead bounces around which gives us a good value for model parameters but not optimal which can ve solved by reducing the learning rate at each step which can reduce the bouncing and SGD might settle down at global minimum after some time.
</p> 
Algorithm: For iteration 'i', a parameter 'a(i)' and cost function C(a(i)), we have the algorithm as follows:-
</p>
Step 1: Randomly shuffle the data set of size m

Step 2: Select a learning rate l

Step 3: Select initial parameter values 'a(0)' as the starting point

Step 4: Update all parameters from the gradient of a single training example, i.e, compute 
	 a(i+1)=a(i)-l*Gradient(C(a(i))).

Step 5: Repeat Step 4 until a local minimum is reached
</p>For Stochastic Gradient Descent-></p>
for i in range m</p>
$\theta_{j} = \theta_{j} - \alpha (y^{^i}_{j}-y^{i}_{j})x_{j}$




Written by
</p>
Kumar Kanishk Singh</p>
Vibhansh Bhatia


Sources:
1. https://optimization.cbe.cornell.edu/index.php?title=Stochastic_gradient_descent#:~:text=Stochastic%20gradient%20descent%20%28abbreviated%20as%20SGD%29%20is%20an,search%20once%20a%20random%20weight%20vector%20is%20picked.
2. https://towardsdatascience.com/stochastic-gradient-descent-clearly-explained-53d239905d31
3. https://www.geeksforgeeks.org/ml-stochastic-gradient-descent-sgd/
4. https://www.geeksforgeeks.org/difference-between-batch-gradient-descent-and-stochastic-gradient-descent/

