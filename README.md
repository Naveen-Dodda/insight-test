# AutoMani
A deep learning model to perfrom segmetation on images provided a robot and provide contours of finger. This is model provided information of all position all the pixels related to finger.The presentation slides for this project are provided as [Google Slides](https://drive.google.com/open?id=1fJP-UhYJfN1BGsrhc85v0OSsd_AJIWoYlNtNQ7Ev6mU)

## Problem Statement
I worked on this project to help a company that is trying to automate manicure process. They have trouble to guide the robot during manicure process ; traditional methods like canny edge detection fails to provide contours of finger during painting process. So I want to introduce a deep learning solution to track down micro movements of finger that can guide robot.



## Setup
This project comes in two repositories. This repository, for general purpose scripts and documentation, and a forked version of the [TensorFlow model](https://github.com/Naveen-Dodda/models) repository which is modified to support finger segmentation application. 
Clone this repo to a machine with an NVidia card (tested on aws p2.xlarge instance).

git clone https://github.com/Naveen-Dodda/insight-ai

## Initial Commit
Lets start with a blank slate: remove `.git` and re initialize the repo
```
cd $repo_name
rm -rf .git   
git init   
git status
```  
You'll see a list of file, these are files that git doesn't recognize. At this point, feel free to change the directory names to match your project. i.e. change the parent directory Insight_Project_Framework and the project directory Insight_Project_Framework:
Now commit these:
```
git add .
git commit -m "Initial commit"
git push origin $branch_name
```

## Requisites

- List all packages and software needed to build the environment
- This could include cloud command line tools (i.e. gsutil), package managers (i.e. conda), etc.

#### Dependencies

- [Streamlit](streamlit.io)

#### Installation
To install the package above, pleae run:
```shell
pip install -r requiremnts
```

## Build Environment
- Include instructions of how to launch scripts in the build subfolder
- Build scripts can include shell scripts or python setup.py files
- The purpose of these scripts is to build a standalone environment, for running the code in this repository
- The environment can be for local use, or for use in a cloud environment
- If using for a cloud environment, commands could include CLI tools from a cloud provider (i.e. gsutil from Google Cloud Platform)
```
# Example

# Step 1
# Step 2
```

## Configs
- We recommond using either .yaml or .txt for your config files, not .json
- **DO NOT STORE CREDENTIALS IN THE CONFIG DIRECTORY!!**
- If credentials are needed, use environment variables or HashiCorp's [Vault](https://www.vaultproject.io/)


## Test
- Include instructions for how to run all tests after the software is installed
```
# Example

# Step 1
# Step 2
```

## Run Inference
- Include instructions on how to run inference
- i.e. image classification on a single image for a CNN deep learning project
```
# Example

# Step 1
# Step 2
```

## Build Model
- Include instructions of how to build the model
- This can be done either locally or on the cloud
```
# Example

# Step 1
# Step 2
```

## Serve Model
- Include instructions of how to set up a REST or RPC endpoint
- This is for running remote inference via a custom model
```
# Example

# Step 1
# Step 2
```

## Analysis
- Include some form of EDA (exploratory data analysis)
- And/or include benchmarking of the model and results
```
# Example

# Step 1
# Step 2
```
