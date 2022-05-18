There are three projects.
The 'Selection' rule and 'is_best' option are equally applied to all projects.

------------------------------- ['Selection' rule] -------------------------------
 1) Specify the 'Option' that you want to use and UNCOMMENT corresponding codes.
 2) Don't forget to COMMENT OUT other 'Options' except the codes you decided to use.
---------------------------------------------------------------------------------- 

------------------------------- ['is_best' option] -------------------------------
 1) Code stops automatically if valid accuracy doesn't improve anymore.
 2) More specifically, training is stopped if there is no improvement for 10 epochs after the valid accuracy reaches the maximum value.
 3) To turn off this option and train the model with fixed epochs, COMMENT OUT code bundles below every '# is_best' comment.
---------------------------------------------------------------------------------- 

================================ Project1 ================================
1. Comparision of 3 classification models: MLP, VGG, and ResNet-18

 - Use 'assignment1.ipynb'.
 - Go to the 13th cell, starting with 'Model Selection' title.
   - There are three 'Options': MLP, VGG, and ResNet-18.
   - Follow the 'Selection' rule.
 (To compare 'models', the optimizer is fixed as Adam and the regularizer is not used for all cases.)

================================ Project2 ================================
2. Comparision of 3 regularization techniques: Dropout, L1 Norm, and L2 Norm

 - Use 'assignment2.ipynb'.
 - You have to revise the codes in the 13th cell, starting with 'Model Selection' title.
   - There are three 'Options' (actually two): MLP with droput, and vanilla MLP.
   - Follow the 'Selection' rule.
 - Go to the 14th cell, starting with 'Optimizer Selection' title.
   - There are three 'Options' (actually two): Adam for drouput, and Adam with L2 norm.
   - Follow the 'Selection' rule.
 - Go to the 15th cell, 'Training' code.
   - Find codes starting with 'Optimizer Selection'.
   - If you want to use 'Option3', COMMENT OUT corresponding codes.
   - If you want to use 'Option1' or 'Option2', COMMENT these codes.
 (To compare 'regularization techniques', the model is fixed as MLP and the optimizer is fixed as Adam for all cases.)

================================ Project3 ================================
3. Comparision of 3 optimization methods: Momentum, AdaGrad, and Adam.

 - Use 'assignment3.ipynb'.
 - You have to revise the codes in the 14th cell, starting with 'Optimizer Selection' title.
   - There are three 'Options': SGD with Momentum, AdaGrad, and Adam.
   - Follow the 'Selection' rule.
 (To compare 'optimization methods', the model is fixed as MLP and the regularization technique is not used for all cases.)
