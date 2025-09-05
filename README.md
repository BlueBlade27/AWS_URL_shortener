# URL Shortener Service 🚀

A cloud-native, serverless URL shortener built with **AWS CDK (Python)**.  
Frontend is hosted on **Amazon S3**, backend powered by **AWS Lambda + API Gateway**, and short URL mappings stored in **DynamoDB**.

---

## 🛠 Architecture
- **S3** – Static website hosting (`index.html`)  
- **Lambda (Python 3.11)** – Business logic for shortening & redirecting URLs  
- **API Gateway** – REST API to expose the Lambda functions  
- **DynamoDB** – Persistent storage for shortened URL mappings  
- **AWS CDK (Python)** – Infrastructure as Code for reproducible deployments  

---

## Notes
- To deploy first go into the cdk directory.
- Then do: cdk synth
- Then: cdk deploy
- Once you are done do: cdk destroy
