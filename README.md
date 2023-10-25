
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

# HOW TO HOST A STATIC WEBSITE ON AMAZON S3
You’ll create an Amazon S3 bucket to hold your static website files and an Amazon CloudFront distribution to serve your website globally. Amazon Route 53 will manage your domain name, and AWS Certificate Manager will provide a valid SSL/TLS certificate.


## SERVICES USED
 

- Amazon S3 
 - Amazon CloudFront 
   -  Amazon Route 53 
   - AWS Certificate Manager r 



## Prerequisites 


You’ll need a few things to get started with this project:

    Static website made up of HTML, CSS, JavaScript, 





## DOCUMENTATION

- to learn more about the project  click this link [tutorial](https://docs.aws.amazon.com/AmazonS3/latest/userguide/website-hosting-custom-domain-walkthrough.html)


## S3 BUCKET POLICY
change arn of the s3

```bash
  {
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::gracee33/*"
        }
    ]
}
```


# Hi, I'm  gracee! 👋


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)


## 🚀 About Me
I'M  GRACE A DATA AND MACHINE LEARNING ENGINEER

