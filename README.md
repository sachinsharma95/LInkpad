# LInkPad - AI-Powered Alumni Networking Platform

![LinkPad Logo](Linkpad.png)

## Project Status: Ongoing (as of October)

### Overview

LinkPad is a web-based alumni networking platform that leverages the power of AI and ML to enhance networking, create career opportunities, and foster institutional growth. This platform provides alumni with the means to connect with their peers, industry professionals, and access job opportunities. Simultaneously, it offers institutes the ability to track their alumni's progress and gain valuable insights into their career paths.

### Problem Statement

In the absence of a dedicated platform, alumni often struggle to connect with their peers and industry professionals from their alma mater. This lack of connection hinders collaboration, learning, mentoring, job discovery, and staying updated on industry trends. Additionally, institutes have no systematic way to track their alumni's progress or gain insights into their career trajectories.

### Solution

**Key Features:**

1. **Alumni Networking:** LinkPad provides a platform for alumni to connect, collaborate, mentor, and explore career opportunities.

2. **Industry Insights:** Keep alumni and institute staff updated on the latest industry standards, career paths, and technological trends.

3. **Fake Information Classifier:** LinkPad incorporates a fake information classifier that identifies and combats misinformation using Django and Natural Language Processing (NLP). The classifier is based on a Bi-directional Recurrent Neural Network (RNN) model with an accuracy of over 92%.

4. **Explanatory Feature:** The platform explains the model's predictions and generates counter-arguments for fake information articles, empowering users to understand and counter misinformation effectively.

### Technical Requirements

To run LinkPad, ensure you have the following dependencies installed:

- Python 3.8 or higher
- Django 3.2 or higher
- TensorFlow 2.9 or higher

### How to Run

To deploy LinkPad, follow these steps:

1. Clone the LinkPad repository:
   ```
   git clone  https://github.com/sachinsharma95/LInkpad
  ```

2 Navigate to the LinkPad directory:
```
cd LInkPad
```
3 Create a virtual environment:

``` python3 -m venv env
```
4 Activate the virtual environment:
```  
  source env/bin/activate
```

5 Install LinkPad dependencies:
```
pip install -r requirements.txt

```

6 Create a database:
```
python manage.py migrate

```
7 Run the LinkPad development server:
```
  python manage.py runserver
```
LinkPad will now be accessible at http://localhost:8000/. The admin interface can be found at http://localhost:8000/admin.

### Additional Information
LinkPad is an ongoing project that already provides valuable tools for alumni, students, and institute staff. The fake information classifier is highly accurate, and the feature explaining model predictions and generating counter-arguments is a valuable asset for understanding and combating misinformation.

Contributions to the project and feedback are welcome. Your support and insights can help enhance the platform's capabilities.
