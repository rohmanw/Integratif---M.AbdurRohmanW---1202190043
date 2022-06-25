# Final Project Report

### Install Laravel 9 on Windows

1. ```markdown
   Required XAMPP for Windows
   Install XAMPP from www.apachefriends.org
   ```


2. ```markdown
   Required Composer for Windows
   Install Composer
   check song composer is installed or not in the command prompt
   ```

![image-20220602114629219](https://user-images.githubusercontent.com/93067781/171827541-42f2bb67-c7a4-40a0-a6d5-fa767d45072b.png)

#### How To Install

1. The first step in installing Laravel is to enter the Command Prompt. The trick is to click Win+R then type cmd and click OK

![image-20220602114522402](https://user-images.githubusercontent.com/93067781/171827422-0131cc9e-db36-4b74-9109-871ec2d72137.png)

2. Before installing Laravel, navigate to Command Prompt or terminal to the file server directory. The file server location on XAMPP by default is in the xampp/htdocs directory.

   ```markdown
   cd \xampp\htdocs
   ```

![image-20220602114527969](https://user-images.githubusercontent.com/93067781/171827518-f3b1c17e-ea26-419e-81b6-0e9ef35c30f5.png)

3. Start the Laravel Install Process

   ```markdown
   composer create-project --prefer-dist laravel/laravel nama_projectmu(rohman)
   ```

![image-20220603154039064](https://user-images.githubusercontent.com/93067781/171827568-bb5976a2-df93-43b0-9751-7f9ff5e36b31.png)

4. Wait until finished

![image-20220603154217062](https://user-images.githubusercontent.com/93067781/171827592-31bcbdf3-7032-4d77-aff0-1db48bc7b3bb.png)

5. Check Laravel Installation in Web Browser

   ```markdown
   After the Laravel file download process is complete, there will be a new folder in the file server directory with a name according to the project name that you previously specified in the /xampp/htdocs folder.
   ```

![image-20220603154504506](https://user-images.githubusercontent.com/93067781/171827628-482dddcd-2b98-4b5a-9ac6-c01db123123a.png)

6. To ensure that Laravel is successfully installed and ready to use, navigate to Command Prompt or Terminal to the directory you created earlier. Then, enter the following command into Command Prompt or Terminal:

   ```markdown
   Php artisan serve
   ```

![image-20220603154614925](https://user-images.githubusercontent.com/93067781/171827652-3cc8b835-e587-4781-8556-56e5bcdd1a24.png)

7.  By default, you will be directed to the server address, which is 127.0.0.1:8000. Later, a homepage will appear with Laravel writing in the middle as shown in the image below:

![image-20220603154701101](https://user-images.githubusercontent.com/93067781/171827668-4f3704fb-2cbf-47bd-a4b6-f274f23b826d.png)

#### **Finished To Install Laravel 9 on Windows**



### Database and RSS

1. Change DB_DATABASE in file .env. according to phpmyadmin.

   ![image-20220625170302208](https://user-images.githubusercontent.com/93067781/175769358-1cf397f1-fde3-49b2-853b-515054ca494d.png)

   

2. Create file for rss table and news table.

   ```markdown
   php artisan make:migration create_rss_table
   php artisan make:migration create_news_table
   ```

3. Create seeder and controller.

   ```markdown
   php artisan make:model Rss --seed --controller
   ```

4. Create news controller.

   ```markdown
   php artisan make:model News --controller
   ```

5. Edit file NewsController.php

   ![image-20220625180230827](https://user-images.githubusercontent.com/93067781/175770716-aeca7621-aebe-449e-afaf-0fe9a9636dcc.png)

   

6. Add Route in routes/web.php

   ![image-20220625180435951](https://user-images.githubusercontent.com/93067781/175770778-6c1a87bb-89c5-45e6-b969-2e5326c22b3c.png)

7. Run migration:fresh, db:seed, and artisan serve

   ```markdown
   php artisan migrate:fresh
   php artisan db:seed
   php artisan serve
   ```

8. Check on database phpmyadmin

   ![image-20220625222521908](https://user-images.githubusercontent.com/93067781/175780155-d2e2f21c-6f22-4feb-a819-2ff0240477cb.png)
   
   ![image-20220625222256957](https://user-images.githubusercontent.com/93067781/175780087-13116723-2056-4e77-8b7b-e899b6b74747.png)
   
8. Check on your browser

   ![image-20220625222726538](https://user-images.githubusercontent.com/93067781/175780228-a7d0836a-011d-4150-b2ba-c49b608e214f.png)
   
   
   
   
