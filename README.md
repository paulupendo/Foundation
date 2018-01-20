# Foundation
Node, Express, JWT, DynamoDB, S3, React, SASS, Bootstrap, Webpack, ES6

**Project Overview:**
- This project is to create a simple web application with JWT user authentication, and a very basic UI. The app will allow the user to register, and login to their account, with their information being stored in DynamoDB.
 

Facebook App
----
- **App ID:** 198030664086002
- **Secret:** 1e58c1b31d0c71f2c108b205de8aef80


Twitter App
----
- **Consumer Key:** cqaZOnlW0brPpEyfZn3GbN3m2
- **Consumer Secret:** Z8RmNQlDmbNVoDcLhpUr8rLWA2g4rFKBiig6sFCJbYbQT1jTIZ


AWS Credentials
----
- **Config Values:**
```
{
    "accessKeyId": "AKIAIR7DCNYBNIUXCKSQ",
    "secretAccessKey": "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",
    "region": "us-east-1",
    "endpoint": "https://dynamodb.us-east-1.amazonaws.com"
}
```
- **DynamoDB Database:**
  - **Name:** foundation_user
  - **Primary Key:** user_id
  - **Example:**
    - **Get:** "user_id" = "8346316610"
    - **Result:**
```
{
  "user_id": "8346316610",
  "first_name": "Dan",
  "last_name": "Schoonmaker",
  "email": "dschoon@gmail.com",
  "avatar_url": "https://lh6.googleusercontent.com/-eO1JU1rM6Q4/AAAAAAAAAAI/AAAAAAAAIMw/HMK4_MDdMBY/photo.jpg?sz=256",
  "locale": "en_US",
  "phone": "555-555-5555",
  "role": "ADMIN",
  "social_profiles": [],
  "created_ts": 1516330320000,
  "last_updated_ts": 1516330320000,
  "version": 1
}
```

- **S3 Bucket**
  - **Name:** foundation-dev-assets
  - **URL:** https://s3.amazonaws.com/foundation-dev-assets
  - **Example File:** https://s3.amazonaws.com/foundation-dev-assets/puppy.jpg
