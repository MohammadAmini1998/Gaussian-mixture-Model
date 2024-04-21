# Customer Segmentation using Gaussian Mixture Model (GMM)

## About Gaussian Mixture Model (GMM)

The Gaussian Mixture Model (GMM) is a probabilistic model that assumes that the data is generated from a mixture of several Gaussian distributions. It is a soft clustering algorithm that assigns a probability to each data point belonging to each cluster. The main idea behind GMM is to maximize the likelihood of the observed data by iteratively adjusting the parameters of the Gaussian distributions.

### How GMM Works

1. **Initialization**: Randomly initialize the parameters of the Gaussian distributions (means, covariances, and mixing coefficients).
2. **Expectation Step (E-step)**: Compute the probability of each data point belonging to each cluster using the current parameters.
3. **Maximization Step (M-step)**: Update the parameters of the Gaussian distributions to maximize the likelihood of the observed data.
4. **Repeat E-step and M-step**: Iterate steps 2 and 3 until convergence, i.e., until the parameters no longer change significantly.

### Dataset

The "Mall Customers" dataset contains the following features:

- Age: Age of the customer
- Gender: Gender of the customer (Male/Female)
- Annual Income: Annual income of the customer
- Spending Score: Spending score of the customer

You can download the dataset from [here](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

### Results

![509a778e-a082-41ce-bd81-2dc59c388ee6](https://github.com/MohammadAmini1998/Gaussian-mixture-Model/assets/49214384/d7dfb4dc-3d67-443c-bfcc-a3a659a9e87c)

### Contributions and Feedback

I welcome contributions, feedback, and suggestions for improvement! If you have any ideas, questions, or insights regarding this project, feel free to reach out and engage in discussions.

Let's continue exploring the exciting possibilities of Machine Learning together! 🚀

By the way, If you find this project helpful or interesting, please star the repository to show your support! 

