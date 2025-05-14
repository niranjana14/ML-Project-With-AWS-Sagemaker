# 🚀 SageMaker Model Training with S3 Integration

This project demonstrates training a machine learning model using **Amazon SageMaker**, with data and model artifacts stored in **Amazon S3**.

---

- `research.ipynb` – Jupyter notebook for SageMaker training
- S3 bucket – Used for input data and model output

---

## ✅ Overview Steps

## 1. Create an S3 Bucket
- Store training data and output model artifacts.

## 2. Prepare Training Data
- Upload your dataset (e.g., CSV) to the S3 bucket.

## 3. Launch SageMaker Notebook Instance or VS Code
- Open `research.ipynb`.

## 4. Set Up SageMaker Role and S3 Paths
- Define the IAM role and S3 input/output locations in the notebook.

## 5. Configure the Estimator
- Use a built-in or custom container (e.g., `SKLearn`).
- Set hyperparameters, instance type, and paths.

## 6. Train the Model
- Run the training job with `.fit()` using the S3 input path.

## 7. Review Output
- Check model artifacts saved in the S3 output path.
- Review logs in the SageMaker console.

## 8.  Deploy Model
- Use `.deploy()` to create a SageMaker endpoint for inference.


## Screenshots 
- Training job in sagemaker
  ![image](https://github.com/user-attachments/assets/a077f101-3b64-4ed6-9525-22b7f92b2eff)

- Model stored in s3
  ![image](https://github.com/user-attachments/assets/b5fc7faa-1c1b-4ffe-bf01-c889e2b594bd)

- Deployment (Endpoint)
  ![image](https://github.com/user-attachments/assets/a86c4d95-0606-4447-9fd8-8943816c87f0)





