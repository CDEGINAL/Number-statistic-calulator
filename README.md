# Number Statistics Calculator


## Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

## Project Setup Steps

1. **Create Project Directory**
   ```bash
   mkdir number_statistics_project
   cd number_statistics_project
   ```

2. **Create and Activate Virtual Environment**
   
   For macOS/Linux:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

3. **Install Required Packages**
   ```bash
   pip install django
   ```

4. **Create Django Project**
   ```bash
   django-admin startproject assignment
   cd assignment
   ```

5. **Create Statistics Application**
   ```bash
   python manage.py startapp statistics
   ```

6. **Copy Project Files**
   - Copy all provided code files into their respective locations in the project structure
   - Ensure all files maintain their proper directory structure as shown below:


7. **Apply Database Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

8. **Run Development Server**
   ```bash
   python manage.py runserver
   ```

9. **Access the Application**
   - Open your web browser
   - Navigate to: http://127.0.0.1:8000/

## Using the Application

1. **Homepage Features**
   - Enter numbers directly in the text area (comma-separated)
   - OR upload a file containing comma-separated numbers
   - View the cart showing count of unique numbers entered

2. **Submitting Numbers**
   - Click the "Calculate Statistics" button after entering numbers
   - You will be redirected to the Results page

3. **Results Page Features**
   Displays the following statistics:
   - Unique Input Numbers
   - Sum of all numbers
   - Mean (average)
   - Median (middle value)
   - Mode (most frequent number)
   - Range (difference between max and min)
   - Prime numbers from the input
   - Armstrong numbers from the input

