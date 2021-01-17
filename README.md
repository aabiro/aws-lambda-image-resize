# aws-lambda-image-resize

* Uploading Images to AWS S3 and resize with AWS Lambda

Clone this repository

`cd aws-lambda-image-resize`

`npm install busboy && uuid && jimp && aws-sdk`

Change the bucket name in the `serverless.yml` file, choose your desired region that supports Lambda

Run `serverless deploy`

You can see the `POST` endpoint created once the function is deployed on the terminal

# To test run:

`curl -H "Content-type: application/json" -d "{"photoUrl":"<PATH-TO-PHOTO-JPG"}" "<GENERATED ENDPOINT>"`
