# Webshop
 Webshop Projekt with HTML, CSS and PHP

 This Project is meant for gathering experience and showcasing my knowledge and abilities in Software Development.
 Wich is the reason you may find more detailed or even mostly unneeded comments and descriptions.
 My goal is to share my thoughts on the different topics or to share my reasoning behind my decisions
 especially when it comes to design.

Project goal is to create a Web shop including HTML, CSS and PHP and excluding any kind of Framework.

Feature list:

User:
Register
Edit Profile
Login system
Permissions
Reset Password

Product:
Create
Edit
Delete
Search

Shopping Cart:
Add Products
Show Items
Edit Items
Delete Items

The list of Features may expand in the future.
For now, there are no Payment systems planned which may change in the future.

Here is an Overview for the directory of the project.
I tried to gather any files wich should not be freely accesible in the app folder.

Directory:

    index.php

    - app

        - user
            user.php
            userdatabasehandler.php
            usercontroller.php

        - product
            product.php
            producthandler.php
            productcontroller.php

        databasehandler.php
        sessionhandler.php

    - public
        home.php
        registration.php

        - viewcomponents
            footer.php

