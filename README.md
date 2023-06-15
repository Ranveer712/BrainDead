# BrainDead



# Problem Statement : Detecting Emotional Sentiment in Cartoons
# Challenge Description:

Social media platforms are widely used by individuals and organizations to express emotions, opinions, and ideas. These platforms generate vast amounts of data, which can be analyzed to gain insights into user behavior, preferences, and sentiment. Accurately classifying the sentiment of social media posts can provide valuable insights for businesses, individuals, and organizations to make informed decisions.

To accomplish this task, a customized private cartoon dataset (original images) of social media posts has been provided, which contains labels for each post's emotion category, such as happy, angry, sad, or neutral.

The task is to build and fine-tune a machine-learning model that accurately classifies social media posts into their corresponding emotion categories, using synthetic images.

To achieve this, the following steps are required:
⭐ Generate synthetic images using any image generation techniques (e.g., GAN, Diffusion Models, Autoencoder Decoder) to augment the dataset and increase its size.
⭐ So for example, we use the images in the category of "happy" to synthetically generate similar images. Repeat the same for each category.
⭐ Use the original and synthetic images to build a machine-learning model that accurately classifies social media posts into their corresponding emotion categories.
⭐ Evaluate the performance of the model using appropriate metrics such as accuracy, precision, recall, and F1-score.
⭐ Compare the performance of the model when trained on the original dataset only, the synthetic dataset only, and the combination of both.
⭐ Analyze the results to determine the effectiveness of using synthetic images for improving classification accuracy.

The dataset consists of a diverse range of cropped cartoon face images. The data has been pre-processed and cleaned, but you can apply additional data cleaning or pre-processing techniques if necessary. You can use any machine learning or deep learning algorithm or technique of your choice to build and finetune your model, as long as it can accurately classify the posts into their corresponding emotion categories.

Based on a previous study, The performance accuracy of the best classification algorithms for emotion detection is 0.906. Your goal is to beat this using your models, but your model should not be overfitting or underfitting.

To evaluate the performance of your model, you will be using standard evaluation metrics such as accuracy, precision, recall, F1 score, and confusion matrix. The submission with the highest evaluation score will be declared the winner. The top submissions will also be invited to present their solutions and insights to the community.



# Evaluation metrics:

F-1 measure, Classification Accuracy, Precision, Recall, Confusion matrix, ROC Curve, AUC ROC score.



