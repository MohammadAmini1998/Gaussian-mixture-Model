# Customer Segmentation using Gaussian Mixture Model (GMM)

The "Mall Customers" dataset contains information about customers of a shopping mall, including their age, gender, annual income, and spending score. The spending score is a metric that represents how much a customer spends in the mall. By analyzing these features, we can gain insights into customer behavior and preferences.

## About Gaussian Mixture Model (GMM)

The Gaussian Mixture Model (GMM) is a probabilistic model that assumes that the data is generated from a mixture of several Gaussian distributions. It is a soft clustering algorithm that assigns a probability to each data point belonging to each cluster. The main idea behind GMM is to maximize the likelihood of the observed data by iteratively adjusting the parameters of the Gaussian distributions.

### How GMM Works:

1. **Initialization**: Randomly initialize the parameters of the Gaussian distributions (means, covariances, and mixing coefficients).
2. **Expectation Step (E-step)**: Compute the probability of each data point belonging to each cluster using the current parameters.
3. **Maximization Step (M-step)**: Update the parameters of the Gaussian distributions to maximize the likelihood of the observed data.
4. **Repeat E-step and M-step**: Iterate steps 2 and 3 until convergence, i.e., until the parameters no longer change significantly.
