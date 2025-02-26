
# Hi, I'm Abhilash Joshi! 👋


# Face Recognition project 

 Introducing my AWS-powered Face Recognition Project, a cutting-edge application leveraging Amazon Web Services' advanced capabilities. This innovative project utilizes AWS's powerful AI and machine learning services to accurately identify and authenticate individuals based on facial features.

By harnessing AWS's robust cloud infrastructure, this project showcases the seamless integration of facial recognition technology into real-world applications. The system is designed to provide secure access control, authentication, and personalized user experiences.




#  Commands 

```bash
    pip install aws-shell

```
```bash
    aws configure

```
```bash
    aws rekognition create-collection --collection-id facerecognition_collection   --region ap-south-1

```
```bash
    aws dynamodb create-table --table-name facerecognition \
    --attribute-definitions AttributeName=RekognitionId,AttributeType=S \
    --key-schema AttributeName=RekognitionId,KeyType=HASH \
    --provisioned-throughput ReadCapacityUnits=1,WriteCapacityUnits=1 \
    --region ap-south-1

```
```bash
    aws s3 mb s3://bucket-name --region ap-south-1

```


