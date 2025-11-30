# adp
Agentic design patterns
 agents


Set up:
Create a new file named requirements.txt and copy the code provided at the end of this section.



Instructions for Langchain
1. Install Pytjong 3.10 or later 
#**** Skip Step 2 as it did not work for me. Go To Step 3*****
2. Create and activate a virtual environment:
	* python -m venv venv
	* source venv/bin/activate     # On Windows: venv\Scripts\activate

3.	Install all required libraries:
python3.14 -m pip install -r requirements.txt
(Optional) Link this environment to your IDE or Jupyter notebook:
#****************

For Google ADK v 1.19 I had to use Python 3.11 as it is not compatible with latest with Python 3.14
Here are instruction 
# Using Python 3.11
python3.11 -m venv adk_env

# Activate it
source adk_env/bin/activate

# Install google-adk
pip install -r requirements.txt

# Add it as a kernel
python -m ipykernel install --user --name=adk_env --display-name="Python 3.11 (ADK)"
