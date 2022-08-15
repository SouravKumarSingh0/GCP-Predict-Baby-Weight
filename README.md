# Predict Baby Weight &middot; [![Build Status](https://img.shields.io/travis/npm/npm/latest.svg?style=flat-square)](https://travis-ci.org/npm/npm)[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
> ### I made this project by Completing the Following Tasks given below in the Qwiklab.

## 🛠 Skills
### GoogleCloudPlatform, github, Machine Learning,TensorFlow...

In this lab we train, evaluate, and deploy a machine learning model to predict a baby's weight. We then send requests to the model to make online predictions.

### What we'll learn

In this lab, we learn:

1. Launch a Vertex AI notebook

2. Carry out local training and distributed training

3. Deploy the ML model as a web service

4. Make predictions with the model

# Setup

## Before you click the Start Lab button

This hands-on lab lets you do the lab activities yourself in a real cloud environment, not in a simulation or demo environment. It does so by giving you new, temporary credentials that you use to sign in and access Google Cloud for the duration of the lab.

### How to start your lab and sign in to the Google Cloud Console

1. Click the Start Lab button. If you need to pay for the lab, a pop-up opens for you to select your payment method.
2. Click Open Google Console. The lab spins up resources, and then opens another tab that shows the Sign in page.
3. If necessary, copy the Username from the Lab Details panel and paste it into the Sign in dialog. Click Next.
4. Copy the Password from the Lab Details panel and paste it into the Welcome dialog. Click Next.
5. Accept the terms and conditions.

## Activate Cloud Shell
1. Click Activate Cloud Shell Activate Cloud Shell icon at the top of the Google Cloud console.
2. Click Continue.
3. You can list the active account name with this command
```shell
gcloud auth list
```
# Perform Tasks
## Task 1. Create the bucket
Create a bucket using the Google Cloud console:

1. In your Cloud Console, click on the Navigation menu, and select Cloud Storage.

2. Click on Create bucket.

3. Choose a Regional bucket and set a unique name (use your project ID because it is unique).

4. Click Create.

## Task 2. Launch a Vertex AI notebook
To launch AI Platform Notebooks:

1. In the Navigation Menu click AI Platform > Dashboard.

2. In the Notebooks card, click View notebook instances.

3. On the Workbench page, at the top, click New Notebook.

4. In the Customize instance menu, select TensorFlow Enterprise and choose the latest version of TensorFlow Enterprise 2.x (with LTS) > Without GPUs.

5. In the New notebook dialog, click the pencil icon to edit notebook properties.

6. For Instance name, use the default name that was pregenerated for you.

7. For Region, select us-central1 and for Zone, select a zone within the selected region.

8. Scroll down to Machine configuration and select n1-standard-2 for Machine type.

9. Leave the remaining fields at their default and click Create.

After a few minutes, the Workbench page lists your instance name, followed by Open JupyterLab.

10. Click Open JupyterLab. A JupyterLab window opens in a new tab.

## Task 3. Clone the course repo

To clone the training-data-analyst repository in your JupyterLab instance:

1. In JupyterLab, click the Terminal icon to open a new terminal.

2. At the command-line prompt, type the following command and press Enter:

```shell
git clone https://github.com/GoogleCloudPlatform/training-data-analyst
```
3. To confirm that you have cloned the repository, in the left panel, double click the training-data-analyst folder to see its contents.


## Task 4. Execute training and prediction jobs

1. In the notebook interface, navigate to training-data-analyst > blogs > babyweight and open train_deploy.ipynb.

2. From the menu, click Edit > Clear All Outputs.

3. From the top right corner, make sure you're using the Python 3 kernel.

4. Read the narrative and click Shift + Enter (or Run) on each cell in the notebook.

# Congratulations!
We learned how to train, evaluate, and deploy a machine learning model in Cloud Datalab.

## Acknowledgements

 - [Predict Baby Weight with TensorFlow on AI Platform](https://googlecoursera.qwiklabs.com/focuses/23334910?parent=lti_session)
 
## Certificate

[Predict Baby Weight with TensorFlow](https://drive.google.com/drive/u/0/folders/1JEXJ0f2EhuZ7g3I77mh5JkBqJidm6Rlh)
