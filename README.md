# Sagemaker-Intro
Quick introduction to Sagemaker to create a notebook, and execute one of the built in tutorials

## Create a Notebook
- Open your [AWS Management Console](https://console.aws.amazon.com/). 
- Select US East (N. Virginia) region
- Navigate to Amazon Sagemaker service.
- Find and click on "Notebook instances" in the menu under "Notebook" on the lefthand side of the page.
- Click on the "Create notebook instance" button on the upper right of the main Notebook instances pane.
  - Notebook Instance Settings
    - Instance name: Name your notebook using the pattern  (firstinitial)(lastname)-p2vptpm-(notebookname)
    - Notebook instance type: (default) ml.t2.medium
    - Elastic Inference: ml.eia1.medium
  - Permissions and encryption
    - (defaults)
  - Network - default
  - Git Repos - default
  - Tags - none
- Click on "Create Notebook Instance"
- What for status to show "InService"

## Run an example
- Click on "Open Jupyter" next to your Notebook instance.
- Navigate to new browser tab wit your Jupyter Notebook.
- Click on "SageMaker Examples" tab at the top of your notebook.
- Find and example you want to explore and click on the "Use" button.
- Add your first initial and lastname to the front of the filename (good practice for any resource on our shared account)
- Click on "Create Copy"
- Create an S3 bucket for the examples - you will need the bucket name for the notebook code
- Fill in the name of your bucket where indicated in the example
