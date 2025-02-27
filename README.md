# Neural-Networks--2

Student Name: Yeshwanth Narige \
ID: 700764035


Question 1: Cloud Computing for Deep Learning 
(a) Elasticity and Scalability in Cloud Computing for Deep Learning (10 points)
Elasticity:

The ability of a cloud system to dynamically allocate and deallocate resources based on workload demands.
Ensures cost-efficiency by scaling resources up during high demand and down during low demand.
Example: Automatically provisioning more GPUs when training large deep learning models and reducing them after completion.
Scalability:

The ability of a cloud system to handle increasing workloads by adding more resources (scaling up or out).
Two types:
Vertical Scaling (Scale-Up): Increasing compute power (CPU, GPU, RAM) of a single instance.
Horizontal Scaling (Scale-Out): Adding more instances/nodes to distribute workloads.
Example: Expanding a distributed training system across multiple GPUs or cloud instances.

(b) Comparison of AWS SageMaker, Google Vertex AI, and Azure ML Studio (10 points)
1. AWS SageMaker
✅ Fully managed ML service with integrated Jupyter notebooks.
✅ Supports TensorFlow, PyTorch, MXNet, and Scikit-learn.
✅ Auto-scaling for distributed training and model deployment.
✅ Supports Nvidia GPUs and AWS Inferentia for optimized deep learning.
✅ Offers MLOps tools like Pipelines, AutoML, and model monitoring.
✅ Best for enterprise-level scalable AI workloads.

2. Google Vertex AI
✅ Unified platform integrating AutoML and custom ML models.
✅ Supports TensorFlow, PyTorch, and Scikit-learn.
✅ Kubernetes-based distributed training for scalability.
✅ Supports GPUs and TPUs for accelerated AI workloads.
✅ Includes Vertex Pipelines, AI Explanations, and AutoML.
✅ Best for data-centric AI with strong AutoML capabilities.

3. Microsoft Azure Machine Learning Studio
✅ Low-code/no-code interface for ML model development.
✅ Supports TensorFlow, PyTorch, ONNX, and Scikit-learn.
✅ Offers hyperparameter tuning and distributed training.
✅ Supports Nvidia GPUs and FPGAs for deep learning.
✅ Provides MLOps, CI/CD integration, and AutoML.
✅ Best for users within the Microsoft ecosystem (Azure, Power BI, Synapse).

Question 3: CNN Feature Extraction with Filters and Pooling (30 points)
Task 1: Implement Edge Detection Using Convolution (15 points)
Explanation:
•	Loads a grayscale image. \
•	Defines the Sobel filters for detecting edges in the x and y directions. \
•	Applies convolution using cv2.filter2D(). \
Displays the original and filtered images using matplotlib \

