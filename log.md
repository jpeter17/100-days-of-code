# 100 Days Of Code - Log

I started this challenge in an effort to build better habits and pursue my interests in coding. My plan going forward is to continue my research on neural networks and look into contributing to open source projects.

### Day 1: July 31, 2019

**Today's Progress**: Worked on understanding neural networks in terms of matrices. I believe I have worked out back propagation for my RGB text predictor, more testing tomorrow.

**Thoughts:**: Going from the simple network used in the flower problem to the one used in the RGB text predictor was incredibly challenging, scaling further shouldn't require too much effort to figure out.

**Link to work:** [Color Picker](https://github.com/jpeter17/color_picker_NN)

### Day 2: Aug 1, 2019

**Today's Progress**: Finished the model for the RGB color predictor and moved on to adding information to the UI. 

**Thoughts:**: Formatting numpy matrices took some doing but wasn't too difficult to figure out. I can't tell if the network is functioning properly. Using a labeled dataset in the next project would make this more clear. 

**Link to work:** [Color Picker](https://github.com/jpeter17/color_picker_NN)

### Day 3: Aug 2, 2019

**Today's Progress**: Did some research on the reasoning behind number of hidden layers and nodes within them. Started a new network, dubbed 'Skribble', that will eventually be able to interpret handwritten digits for the MNIST data set.

**Thoughts:**: Did not make as much progress as I wanted to on this. I did my coding on a bus to Portland and did not think to eat before hand. The information I learned on hidden layers and neurons was very interesting.

**Link to work:** [Skribble](https://github.com/jpeter17/Skribble)

### Day 4: Aug 5, 2019

**Today's Progress**: Updated some things in the Skribble Network and found some bugs in calculating the change in weight that I need to keep working on. 

**Thoughts:**: Extremes of the sigmoid function return a derivative of zero. This is causing me some issues in change in weight. I need to look into changing the activation function to something that doesnt have a derivative tending to 0 or make sure my z-values stay relatively close to 0 

**Link to work:** [Skribble](https://github.com/jpeter17/Skribble)

### Day 5: Aug 6, 2019

**Today's Progress**: Worked on some questions from previous rounds of Google Code Jam and LeetCode. Completed first 4 modules of Google's Machine Learning Crash Course. 

**Thoughts:**: I have been looking into signing up for the upcoming Google Kick Start Competition. I will work on past problems in the upcoming days to decide. The Machine Learning crash course has introduced me to some new technologies that will be useful in the Skribble network as well as much more memory friendly ways to visualize data.

### Day 6: Aug 7, 2019

**Today's Progress**: Did problems from previous rounds of Google's Kick Start competition to prepare for the upcoming round. Additionally completed some more modules in the machine learning crash course.

**Thoughts:**: I know that I have the ability to score at least a few points in Kick Start so I figure I might as well participate. I have picked up a few books to hone my algorithm and data structure ability in preperation. 

### Day 7: Aug 8, 2019

**Today's Progress**: More modules from the machine learning crash course. Learned about bucketization of data and it's usefulness in addition to the FTRL optimizer. The results are impressive. 

**Thoughts:**: Bucketization might assist me with the accuracy of the Skribble Network. Binning the brightness values into fewer groups such as (dark, dim, bright) might increase accuracy. FTLR optimization will allow adjustment of learning rates for the outermost pixels that will almost always be classified as dark. 

### Day 8: Aug 9, 2019 

**Today's Progress**: Some LeetCode problems to continue practicing data structures and algorithms along with more machine learning crash course modules on logistic regression. 

**Thoughts:**: The issue with the Skribble network probably has to do with me using part of logistic regression while still using a linear cost function. Log cost could solve these issues but I will probably end up using TensorFlow.

### Day 9: Aug 10, 2019 

**Today's Progress**: More Machine Learning crash course modules. Finally getting into non-linear classification models. Some interesting stuff.  

**Thoughts:**: I don't fully understand how layers and nodes relates to what correlations the model can make. Is it trial and error or is there some intuition you can gain for it?

### Day 10: Aug 11, 2019 

**Today's Progress**: Today's machine learning module ended up being the MNIST digits problem I was trying to solve a few days ago. Currently struggling through adjusting hyperparameters to achieve accuracy > 95%.

**Thoughts:**: I feel like I'm on the right track with the parameters but then I seem to run into walls that I can't get past. Accuracy goes up to a certain point before overfitting.

### Day 11: Aug 12, 2019

**Today's Progress**: Finished up the machine learning crash course. Getting the MNIST digit dataset model up to a 96% accuracy was a good feeling. Lots of information about biases today.

**Thoughts:**: A lot of content to think about today. There are so many different ways that data can muddy up a model. It would be neat to get this implemented onto a website that you can draw your own digits into. 

### Day X: 

**Today's Progress**: 

**Thoughts:**: 

**Link to work:** [Skribble](https://github.com/jpeter17/Skribble)


