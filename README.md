
# A Generative Approach to Mitigate Bias in Face Matching using Learned Latent Structure

This work tackles the problem of bias in face matching algorithms. Face matching refers to the task of matching a low-resolution face image of a person with a high-resolution
face image of the same person and has applications in security and personalization. Algorithmic bias is the difference in performance of an algorithm based on demographic descriptors of various users. Such bias can significantly reify and amplify societal biases and make certain advancements in technology benefit one section of the society while hurting the other.
This work proposes a generative AI framework that can counter multiple kinds bias (e.g., gender bias and age bias) at the same time. 
%
The framework consists of two major components: a variational auto-encoder (VAE) that converts the images into their more generic underlying representation, and second, a neural network architecture that uses the above representations to undertake multi-label classification. A generative approach is useful in ensuring that the
system learns to deal with the underlying (latent) structure
of the data for better generalizability and bias reduction.The approach is tested over a public image dataset and found to be effective at reducing bias while maintaining high accuracy.
