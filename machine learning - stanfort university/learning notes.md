## week 1

### introduction
#### what is machine learning?
1. supervised learning
* regression problem
* classification problem
2. unsupervised learning

### model representation and cost function
1. model representation
* h(x) = a + bx
2. cost function
* J(a,b) = squared error

### parameter learning
1. gradient descent
* a := a - learnining_rate * learning_direction
* gradient descent for linear regression

### linear algebra review
1. matrices and vectors
* matrix: no. of rows * no. of columns
* matrix elements: Aij
* vector: an n * 1 matrix (n dimensional vector)
* vector element: yi
2. addition and scalar multplication
* matrix addition
* scalar(number) multiplication
3. matrix vector multiplication
* A (m * n) * A (n * 1) = A (m * 1)
* prediction_vector = data_matrix * parameter_vector
4. matrix matrix multiplication
* A (m * n) * A (n * o) = A (m * o)
* prediction_matrix = data_matrix * hypothesis_matrx
5. matrix multiplication proporties
* A * B != B * A
* (A * B) * C == A * (B * C)
* identity matrix: A * I = I * A = A
6. inverse and transpose
* matrix inverse: A (m * m) * A-1 = A-1 * A = I
* matrix transpose: AT

## week 2

### multivariate linear regression
1. multiple features
2. gradient descent for multiple variables
3. gradient descent in feature scaling
* idea: make sure features are on a similar scale
* feature scaling: make every x between [-1,1]
* mean normalization: (xi - u)/(maximum-minimum)
4. gradient descent in learning rate
* Make a plot with number of iterations on the x-axis and J(a,b) on the y-axis
5. features and polynomial regression
* feature engineering

### computing parameters analytically
1. normal equation
* normal equation vs gradient descent
2. normal equation noninvertibility
* redundant features
* too many features (m<=n)

### submitting programming assignments





