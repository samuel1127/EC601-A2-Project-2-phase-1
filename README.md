# EC601-A2-Project-2-phase-1
Tutorial: Set up the Natural Language API

Google Cloud console (https://support.google.com/cloud/answer/3465889?hl=en&ref_topic=3340599)

1. Create a project
2. Enable billing
3. Enable the API
4. Set up authentication
5. Create a service account and download the private key file
6. Install and initialize the gcloud CLI
7. Test the SDK and authentication
8. Install the Natural Language API client library


Sentiment Analysis Tutorial (https://cloud.google.com/natural-language/docs/sentiment-tutorial)

1. Analyzing document sentiment (https://cloud.google.com/natural-language/docs/sentiment-tutorial#analyzing_document_sentiment)
2. Run the sample
   
   a. Download the samples from Google Cloud Storage:
   
      gsutil cp gs://cloud-samples-tests/natural-language/sentiment-samples.tgz .
      
      gsutil is usually installed as a part of gcloud CLI. To install the latest version of gcloud CLI, please refer to gcloud CLI documentation.
      
   b. Unzip those samples, which will create a "reviews" folder:
   
      gunzip sentiment-samples.tgz
      
      tar -xvf sentiment-samples.tar
      
   c. Run our sentiment analysis on one of the specified files:
   
      python sentiment_analysis.py reviews/bladerunner-pos.txt
      
      
 Code：
 
 https://970-a37b5f1e-487a-42a2-b913-1af5a61cde50.cs-us-east1-vpcf.cloudshell.dev/files/download/?id=2a04aeea-ab73-4e33-a15d-c0b034751a27
