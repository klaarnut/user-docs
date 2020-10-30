# LinkedIn Login Setup

Setup requires a LinkedIn membership and a LinkedIn app must be created.

## Creating a LinkedIn App

1. Go to <https://www.linkedin.com/developers>, sign into your LinkedIn account.

2. The top menu bar, click "My Apps", then click "Create app".

![image](images/login_social_linkedin/linkedin_01.png)

3. Create your App.

![image](images/login_social_linkedin/linkedin_02.png)

## Once you have LinkedIn App information, you can set up Login as LinkedIn as follows

1. Go to <https://www.linkedin.com/developers>, sign into your LinkedIn account.

2. Click "My Apps", select your app name.

![image](images/login_social_linkedin/linkedin_03.png)

3. Click "Auth tab", click the eye icon to display password.

![image](images/login_social_linkedin/linkedin_04.png)

4. Go to website editor -> Site -> System Pages -> Login, click on Login form to open Login setting, to enable LinkedIn Login Setup.

   1. Select LinkedIn tab.
   2. Insert App ID for LinkedIn Client ID and App Secret for LinkedIn Client Secret.
   3. Click OK to add these values to your form.
    - Close the Site Config window.
  
    ![image](images/login_social_linkedin/linkedin_login_config_01.jpg)

     - Click "Save" in the editor page.

    ![image](images/login_social_linkedin/img_linkedin_login_config_03.png)

    **** กรณีตั้งค่าไว้แต่ยังไม่เปิดให้ user ใช้งาน สามารถ ปิด/เปิดปุ่ม Social Login ได้

    A.  On Login Setting, click open the switch button.

    B.  Click "Preview".

    C.  Click "Save" to save all of your setting above.

    ![image](images/login_social_linkedin/linkedin_login_config_02_2.png)

5. The LinkedIn Login single sign-on is available for your user to login to your website without make a new register.
