# SmS_Spam_Classifier

## Overview
This repository contains the code for an SMS Spam Classifier built using machine learning algorithms. The model classifies incoming SMS messages into **Spam** and **Not Spam** categories based on the message content.

## Setup and Installation

### 1. **Setup Virtual Environment**
   - Open the terminal.
   - Install the virtual environment package if you haven't already:
     ```bash
     conda create -p venv python=3.9 -y
     ```
   - Create and activate a virtual environment:
     ```bash
     virtualenv venv
     conda activate venv/
     ```

### 2. **Install Requirements**
   - Install all the required dependencies by running:
     ```bash
     pip install -r requirements.txt
     ```

### 3. **Set Up the Jupyter Notebook**
   - To run Jupyter Notebook in your virtual environment:
     ```bash
     pip install ipykernel
     pip install jupyter notebook
     ```
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```

### 4. **Run `app.py`**
   - To run the main Flask application:
     ```bash
     python app.py
     ```

### 5. **Deploy on Render**
   To deploy the application on **Render.com**, follow these steps:

   1. Go to [Render.com](https://dashboard.render.com/web).
   2. Click on **New** and select **Web Service**.
   3. Choose **Build and deploy from a Git repository** and click **Next**.
   4. In the **Settings** page, follow these steps:
      - Add the repository URL (`https://github.com/amitpanchal319/Spam-Classifier.git`).
      - Set the build and start commands.
   5. Click **Manual Deploy** and select **Deploy with Latest Commit**.
   6. Wait for 2-3 minutes for the deployment to complete.
   7. After the deployment, your application will be live at the following url : 


## Hurray, Enjoy the Code! 🎉

---

### Author: Amit Panchal
