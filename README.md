java cA3 (16%) Submission due on 14 April 2023 at 11.59pm (Week 13 Friday, no extensions
will be entertained)
Write a single python file to perform the following tasks:
(a) Perform gradient descent to minimize the cost function 1() =
6 with an initialization of = 1.0.
(b) Perform gradient descent to minimize the cost function 2() = cos
2() with an initialization of =
1.2 (where is assumed to be in radians).
(c) Perform gradient descent to minimize the cost function 3(, ) = ( + 2 ? 7)
2 + (2 + ? 5)2 with
an initialization of (, ) = (0.5, 2.5).
Submit a single python file with filename “A3_StudentMatriculationNumber.py” (like “A3_A1234567R.py”).
It should contain a function A3 (do not rename function name in this assigment) that takes the following
inputs and returns the following outputs in the following order:
Python function inputs:
 learning_rate: A fraction that falls between 0 and 0.2 (inclusive of 0 and 0.2), e.g., 0.1, etc.
num_iters: A positive integer specifying the number of gradient descent iterations for each
minimization task. Note that for the purpose of this exercise, you do not need to check for convergence. Just
simply run the gradient descent algorithm for num_iters iterations.
Python function outputs in the following order:
a_out: numpy array of length num_iters containing the updated values of . For example,
a_out[0] is the value of after the first round of gradient descent (NOT the initialized value of ). (2%)
 f1_out: numpy array of length num_iters containing the updated values of 1. For example,
f1_out[0] is the value of 1 after the first round of gradient descent, i.e., the value of 1 given
a_out[0]. (2%)
 b_out: numpy array of length num_iters containing the upd代 写program 、 Python
代做程序编程语言ated values of . For example,
b_out[0] is the value of after the first round of gradient descent (NOT the initialized value of ). (2%)
2_out: numpy array of length num_iters containing the updated values of 2. For example,
f2_out[0] is the value of 2 after the first round of gradient descent, i.e., the value of 2 given
b_out[0]. (2%) c_out: numpy array of length num_iters containing the updated values of . For example,
c_out[0] is the value of after the first round of gradient descent (NOT the initialized value of ). (2%)
 d_out: numpy array of length num_iters containing the updated values of . For example,
d_out[0] is the value of after the first round of gradient descent (NOT the initialized value of ). (2%)
 f3_out: numpy array of length num_iters containing the updated values of 3. For example,
f3_out[0] is the value of 3 after the first round of gradient descent, i.e., the value of 3 given
c_out[0]and d_out[0] (4%)
Please use the python template provided to you. Remember to rename “A3_StudentMatriculationNumber.py”
using your student matriculation number (but in this assignement do not rename “A3” function). For example,
if your matriculation ID is A1234567R, then you should submit “A3_A1234567R.py” that contains the function
“A3”. Please do NOT zip/compress your file. Because of the large class size, points will be deducted if
instructions are not followed. The way we would run your code might be something like this:
>> import A3_A1234567R as grading
>> learning_rate = 0.1
>> num_iters = 10
>> a_out, f1_out, b_out, f2_out, c_out, d_out, f3_out \
= grading.A3(learning_rate, num_iters)
Submission folder: Canvas/EE2211/Assignments/Assignment 3

         
加QQ：99515681  WX：codinghelp
