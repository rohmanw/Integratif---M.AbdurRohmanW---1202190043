# Install Laravel 9 on Windows

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
