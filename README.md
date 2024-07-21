# Transfer-Learning-Using-MobileNetV2
Used the MobileNetV2 model, which is pre-trained on the ImageNet dataset, to perform a related task in transfer learning. By leveraging the knowledge from its initial training, the model can effectively tackle similar image recognition tasks with a smaller dataset and fewer computational resources.

## Transfer Learning
Transfer learning is a technique in machine learning where a model trained on one task is used as the starting point for a model on a second task. This can be useful when the second task is similar to the first task, or when there is limited data available for the second task.

## Freezed and Trainable Layers
In transfer learning, there are two main components: frozen layers and modifiable layers.

1. Frozen Layers: These are the layers of a pre-trained model that are kept unchanged during the fine-tuning process. Frozen layers retain the knowledge learned from the original task and are used to extract general features from the input data.
2. Modifiable Layers: These are the layers of the model that are adjusted or re-trained during fine-tuning. Modifiable layers learn task-specific features from the new dataset. By focusing on these layers, the model can adapt to the specific requirements of the new task.

## Advantages of Transfer Learning
1. Speed up the training process
2. Better performance
3. Handling small datasets

## Disadvantages of Transfer Learning
1. Domain Mismatch
2. Overfitting
3. Complexity
