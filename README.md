# Setting up the project
* pip install virtualenv
* python -m venv localenv
* source localenv/bin/activate
* pip install -r requirements.txt

# Train model 
* **python main.py -m train**

# Test model  "testfile" 
Input data for test is in file **testfile**
* **python main.py -m test**
