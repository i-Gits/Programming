
<details>

  <summary>Python for Windows</summary>

  ![image](https://github.com/user-attachments/assets/c25e4f63-1e66-42de-8749-1b800c3d6d3d)

  ![2025-01-20 03_07_43-Python 3 13 1 (64-bit) Setup](https://github.com/user-attachments/assets/604be899-802b-4ac2-83e6-044c0f415c2a)

  <details>
    <summary>
      <!DOCTYPE html>
      <html>
      <body>
        <h1><a href="https://docs.python.org/3.13/tutorial/index.html">Online Tutorial!</a></h1>
      </body>
      </html>
    </summary>

    ![image](https://github.com/user-attachments/assets/54f21836-9e8c-44d5-acf0-a4d3d5801bf8)
  </details>

  <details>
    <summary>
      <!DOCTYPE html>
      <html>
      <body>
        <h1><a href="https://docs.python.org/3.13/index.html">Documentation!</a></h1>
      </body>
      </html>
    </summary>

    ![image](https://github.com/user-attachments/assets/9c91f388-d1fe-4d3d-a520-83a30fbd74d0)
  </details>

</details>

# 2 Python Installation Verification 

<details>

  <summary>Python and pip</summary>

  <details>
    <summary>python --version</summary>
    ![image](https://github.com/user-attachments/assets/c3956807-e453-42da-b3e3-de9f805c4e72)
  </details>

  <details>
    <summary>pip --version</summary>
    ![image](https://github.com/user-attachments/assets/a8c857ac-1e20-421d-8133-72574241f3ab)
  </details>

</details>

# VSCODE

<details>
  <summary>Create folder named api</summary>
  ![image](https://github.com/user-attachments/assets/b1bb08e2-7446-481a-adfd-e8d7dbf8988f)
</details>

<details>
  <summary>Open VSCode</summary>
  ![image](https://github.com/user-attachments/assets/48dfef19-7b60-41e1-bddf-1ec333c8e0c7)
  ![image](https://github.com/user-attachments/assets/eafab471-a2c7-4cdc-9e47-baace1f98adf)
</details>

<details>
  <summary>Run virtual environment command</summary>
  ![image](https://github.com/user-attachments/assets/ffa7987c-0420-44bc-b8df-7a33dff52fdb)
  ![image](https://github.com/user-attachments/assets/0e723214-f767-48e5-833f-922abcafa109)
  ![image](https://github.com/user-attachments/assets/13f36f9e-3969-4070-9fff-7cea63cee69c)
</details>

<details>
  <summary>Activate Environment and Install Django</summary>
.\env\Scripts\Activate

![image](https://github.com/user-attachments/assets/cc273c3f-7a18-4b9b-aa3f-b6d3a0a7bfce)

(env) indicates that the virtual environment is active.

<details>
  <summary>Install Django</summary>

  ```
  pip install django
  ```

  ![image](https://github.com/user-attachments/assets/ffae73ef-ab67-4755-84c7-8e965bc7438f)
  ![image](https://github.com/user-attachments/assets/f68803a4-0a9f-4396-9634-fc2980e796fd)
</details>

<details>
  <summary>Verify Installation</summary>

  ```
  pip install djangorestframework
  ```

  ![image](https://github.com/user-attachments/assets/1add4981-2bfa-4adb-840e-1bce6d9103d8)

  ```
  pip install djangorestframework-simplejwt
  ```
  ```
  pip install django-cors-headers
  ```
  ![image](https://github.com/user-attachments/assets/7b3d2640-d31c-4df1-89b9-a5352ee617d9)


</details> 

</details>


# Create the Django Project

<details> <summary>

  ```
 django-admin startproject connectly_project

  ```

</summary>

![image](https://github.com/user-attachments/assets/9f34e2d7-9e4a-4ab1-a722-621072c46b7d)
<br>
![image](https://github.com/user-attachments/assets/15cbc84a-22c3-46d1-b7b8-955c5172bb0e)
<br>

![image](https://github.com/user-attachments/assets/1ff1e6f6-db06-4817-8586-b37d5c7b6ad6)

<br>
Move to newly created project folder


```
cd connectly_project

```
  
![image](https://github.com/user-attachments/assets/b49b9698-fcd2-413d-98ba-5ab0607c54bd)

</details>

# Configure Django REST Framework (DRF)

<details>

  <summary> 
 
    ```
    connectly_project/settings.py
    ```
  </summary>

  ![image](https://github.com/user-attachments/assets/e95b85ef-1f5e-4658-ac63-ded88e0f9b14)
<br>
  ![image](https://github.com/user-attachments/assets/3c25a16f-5fe1-479e-8379-71356272bdd8)
  
</details>

<br>


# Run Initial Migrations

<details>

  <summary> 
  Using this:

    ```
    python manage.py migrate
    ```
    
  </summary>

  ![image](https://github.com/user-attachments/assets/c9ba077b-069b-4937-a423-931e5d68b176)
  ![image](https://github.com/user-attachments/assets/255f2a39-7e60-47c9-b8af-cb8007f76e7c)


</details>

<br>



# Start the Django Development Server

<details>

  <summary> 
    
  ```
  python manage.py runserver
  ```
  </summary>

  
</details>

<br>


# Errors Encountered

<details>

  <summary> 
  Cannot Access
  </summary>

![image](https://github.com/user-attachments/assets/052c3507-15c9-4b28-bc15-b590672b9be0)

![image](https://github.com/user-attachments/assets/97bf7e43-45d6-417e-883c-b2667d31864a)

![image](https://github.com/user-attachments/assets/dc46810b-8bba-4bf4-8ff5-fe39868d12dc)

  
</details>

<br>


# Solution

<details>

  <summary> 
  Forgot to include 【include】
  </summary>

  ![image](https://github.com/user-attachments/assets/aeb2b78b-e034-4926-902e-a088497a5c1d)

  ![image](https://github.com/user-attachments/assets/2c75863d-5c8f-4316-9ef9-bb91669605dc)
<br>
<br>

Reactivated Environment 

【Open Terminal】>【Access API Folder】>【Activate: env\Scripts\activate.bat】>【Check if Django is Installed】>
【pip install django】<br> >【django-admin --version】>【Run server again: cd connectly_project
python manage.py runserver】 SUCCESS!
<br>

  ![image](https://github.com/user-attachments/assets/cc727c48-1310-4109-b4fe-e9a4939bdf6e)

![image](https://github.com/user-attachments/assets/d589d7d9-e205-4c33-863e-3bfb8315373e)

  ![image](https://github.com/user-attachments/assets/9de1b5af-60f6-4775-b2c1-0be735bd9104)


</details>

<br>


# Results

<details>

  <summary> 
  
  </summary>
  
![image](https://github.com/user-attachments/assets/3c056c03-de5a-498a-afa1-547b9a83e6c2)

  
</details>

<br>


# Superuser

<details>

  <summary> 
  python manage.py createsuperuser

  </summary>
  try again
  
![image](https://github.com/user-attachments/assets/d55ff690-ef87-4186-a203-9f468712c93b)

  ![image](https://github.com/user-attachments/assets/638a5d4d-7948-4849-939a-b9f4d84b268c)


![image](https://github.com/user-attachments/assets/ae896567-f49d-421c-a926-3e5ac4d30af4)
![image](https://github.com/user-attachments/assets/17d06d1e-8dcb-4361-bc81-73bcc7fb0485)

</details>

<br>
