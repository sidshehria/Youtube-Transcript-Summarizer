# YouTube-Video-Summariser
Chrome Extension which will make a request to a backend REST API where it will perform NLP and respond with a summarized version of a
YouTube transcript.


## Requirements
- The following python modules must be installed to run the API
  - ```flask```
  - ```youtube-transcript-api```
  - ```transformers```

## Instructions
- Run ```app.py``` to start the summarizer API.
- Load the custom extension into any Chromium browser.
- Go to any YouTube video and click on the extension logo to start summarizing.
