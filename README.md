<div align="center">
<img src="media/images/logo_cropped_nobg.png" alt="papers & pens" width="150" height="90" center>
</div>

<div style="text-align: center;">
  <h1><b><u>Papers & Pens E-commerce Website</h1></b></u>
</div>

<br>

<h2><b> Project Dependencies and Packages </h2></b>

<h3><b><u>Project Dependencies</b></u></h3>
<ul>
    <li>asgiref==3.7.2</li>
    <li>coverage==7.2.7</li>
    <li>Django==4.2.3</li>
    <li>django-countries==7.5.1</li>
    <li>flake8==6.0.0</li>
    <li>isort==5.12.0</li>
    <li>mccabe==0.7.0</li>
    <li>Pillow==10.0.0</li>
    <li>pycodestyle==2.10.0</li>
    <li>pyflakes==3.0.1</li>
    <li>six==1.16.0</li>
    <li>sqlparse==0.4.4</li>
    <li>typing_extensions==4.7.1</li>
</ul>


<h3><b><u>Project Packages</b></u></h3>
<ul>
    <li>account</li>
    <li>acccount/migrations</li>
    <li>basket</li>
    <li>basket/migrations</li>
    <li>basket/tests</li>
    <li>core</li>
    <li>store</li>
    <li>store/migrations</li>
    <li>store/tests</li>
</ul>

<br>

<h2><b> How to Run the Project </h2></b>

<h3><b><u>General Instructions</b></u></h3>
<hr>

<ol>
    <li style="font-weight: bold;">
        <b>Make sure that the virtual enviornment is activated</b>
        <p>
            To activate a virtual environment from the command line interface (CLI), use the corresponding command for your operating system.
            <br><br>
            <b>On Windows:</b> <u>path\to\env\Scripts\activate</u>
            <br><br>
            Note: Replace <u>path\to\env</u> with the actual path to the virtual environment directory (venv) on your local device.
            <br><br><br>
            <b>On macOS and Linux:</b> <u>source path/to/env/bin/activate</u>
            <br><br>
            Note: Replace <u>path/to/env</u> with the actual path to the virtual environment directory (venv) on your local device.
        </p>
    </li>
    <li style="font-weight: bold;">
        <b>Run the server</b>
        <p>
            Input the command <u>python manage.py runserver</u> or <u>python3 manage.py runserver</u> on your terminal/CLI
        </p>
    </li>
    <li style="font-weight: bold;">
        <b>Access the website</b>
        <p>
            The runserver command should generate a local address to access the website. <br>
            Since the server is running locally, this is usually <u>http://127.0.0.1:8000</u>. 
        </p>
    </li>
</ol>

<br>

<h3><b><u>Customer View</b></u></h3>
<hr>

<ol>
    <li style="font-weight: bold;">
        <b>Log in or create an account</b>
        <p>
            Click the corresponding buttons on the upper right corner of the website and input the necessary information.
        </p>
    </li>
    <li style="font-weight: bold;">
        <b>Navigate and use website as needed</b>
        <p>
            Customers may filter products based on their needs and add these to their basket, as well as editing their basket (deleting items or updating the quantity) before proceeding to check-out. <br><br>
            The website was designed to be intuitive to minimize confusion and maximize the user experience.
        </p>
    </li>
</ol>


<br>

<h3><b><u>Admin View</b></u></h3>

<ol>
    <li style="font-weight: bold;">
        <b>Access the admin page</b>
        <p>
            Add <u>/admin</u> to the end of the standard URL of the website.
            <br><br>
            An example would be <u>http://127.0.0.1:8000/admin</u>
        </p>
    </li>
    <li style="font-weight: bold;">
        <b>Log in as an admin</b>
        <p>
            Input the following account details: <br><br>
            <b>Username:</b> admin<br>
            <b>Password:</b> admin
        </p>
    </li>
    <li style="font-weight: bold;">
        <b>Navigate and use website as needed</b>
        <p>
           Admins of the website are given the autonomy to add, delete, or edit the products that are displayed on the front-end of the website.
        </p>
    </li>
</ol>