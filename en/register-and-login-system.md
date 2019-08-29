# Register and Login System

To​ allow​ website​ visitor​s​ to​ register​ in​ your​ website​ as​ a​ member for​ purpose such​ as​ some​ privilege page​ access​ or​ some​ part​ of​ website​ admin​ interface for​ some​ exclusive​ users,​ you can​ activate​ the​ Built-in Login​ System​ to​ allow​ users to​ use​ their​ current​ account​ from​ **Google​ Email, Facebook, Twitter, LINE**, and​ also​ the​ direct register​ with​ their​ email​ address​ is​ support​ed.

## Activate Google for website register and login system

Google Login Setup for Built-in Channels in your website

![image](images/login_system.png)

Google Login Setup for Built-in Channels requires Google API Setup. Don't worry if you don't feel familiar with Google API Setup, you can follow easy setup below.

1. Open Google Console website at https://console.developers.google.com/ . Login with your google email (Gmail) or register if you don't have one.

2. In Google APIs page, click **Create** for setting your new Google API.

![image](images/loginSystem1.png)

3. Insert your Project Name, and click **Create**.

![image](images/step3.png)

4. Once the new project has been created, at Google APIs select your created project and click **Credential**.

![image](images/step4.png)

5. In Create credentials drop-down list, select OAuth client ID

![image](images/6.png)

6. Then, select **Configure consent screen**.

![image](images/mkt9.png)

7. Create your **Product name shown to users** and website URL at **Homepage URL**.

For example: Product name shown to users : Calm Seas
Homepage URL : http://calmseas.netwaysite.com/

![image](images/step7.png)

8. At **Create OAuth client ID** page.
1) Select **Web application**
2) Create a name for recognizable
3) Insert **Authorized JavaScript origins** (Your website URL)
4) Insert **Redirect URL***

*Please login to your website editor -> Site  -> System, select "Login" under Member. Click on any area of Login widget to open Login Setting. Click on Social Login, and copy URL from Google Login Redirect URL*

![image](images/loginSystem5.png)

5) Don't forget to click **Save**.

![image](images/loginSystem2.png)

9. The **Client ID** and **Client Secret** are showing that you can copy before leaving this page by clicking **OK**.

![image](images/mkt12.png)

10. Once you clicked OK to leave OAuth client, at Google APIs page , select **Library**.

![image](images/mkt13.png)

11. Search for the following API setups to **Enable** them.

![image](images/loginSystem3.png)

Click ***Enable*** to activate the API.*

![image](images/loginSystem4.png)

12. Go to website editor -> Site -> System Pages -> Login, click on Login form to open Login setting. Enable Google Login Setup.

![image](images/loginSystem0.png)

1) Slide the slidable button to activate Google Login
2) Insert Client ID and Client secret from number 9 to Google Login Setup, and click OK to complete setting.

*(You can find details from number 9 at Google API, menu Credential, click on the created project.)*

3) Click OK to add these values to your form.

4) On Login Setting, click **Apply** to apply your setting.

![image](images/loginSystem6.png)

5) Click **Save** to save all of your setting above.

13. The Google Login single sign-on is available for your user to login to your website without make a new register.

If Google Login returns error when visitors try to login, please contact your host provider to allow google rule_id in ModSecurity by this guide. 

##​Facebook Login Setup for Built-in Channels in your website

Go to https://developers.facebook.com/apps , select Create a New App.

Insert Display Name and Contact Email you want facebook to connect with your website. Then click Create App ID.

Insert the correct Security Check.

Next page, look for product Integrate Facebook Login and select Confirm.

At Facebook API management dashboard, find Facebook Login, and insert OAuth redirect URIs and Save Changes. (You can find OAuth redirect URIs in your website editor -> Site -> System Pages -> Login, click on Login form to open Login setting, look for Login Callback URL for facebook.)

Go to Settings -> Basic, to insert Privacy Policy URL. If you have a page to provide Privacy Policy on your website, if not, you can insert your website URL.

Select + Add Platform to continue.

Select Platform as Website.

Insert your website at Site URL and click Save Changes.

Next page, set the Status as On.

Confirm the setting.

Look for App Secret, and select Show.

Facebook API management page will display App ID and App secret.

Login as admin to your website.

Go to website editor -> Site -> System Pages -> Login, click on Login form to open Login setting, to enable Facebook Login Setup.

User the data of App ID and App secret from number 13 to insert at Facebook Login Setup.
