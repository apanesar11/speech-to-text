# speech-to-text
## How to run program
1. Install the google cloud sdk (see [here](https://cloud.google.com/sdk/docs/install))
2. Upload your apiCredentials.json file to the root directory
3. Run the following commands:
   ```
   export GOOGLE_APPLICATION_CREDENTIALS=apiCredentials.json
   gcloud auth activate-service-account --key-file=apiCredentials.json --project=helpful-brand-300402
   python3 main.py
   ```
