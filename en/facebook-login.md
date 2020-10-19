# ​Facebook Login Setup

1. Go to <https://developers.facebook.com/apps> , select **Create a New App**.

2. Insert **Display Name** and **Contact Email** you want facebook to connect with your website. Then click **Create App ID**.

3. Insert the correct **Security Check**.

4. Next page, look for product **Integrate Facebook Login** and select **Confirm**.

5. At Facebook API management dashboard, find **Facebook Login**, and insert **OAuth redirect URIs** and **Save Changes**. _(You can find OAuth redirect URIs in your website editor -> Site -> System Pages -> Login, click on Login form to open Login setting, look for Login Callback URL for facebook.)_

6. Go to **Settings** -> **Basic**, to insert **Privacy Policy URL**. If you have a page to provide Privacy Policy on your website, if not, you can insert your website URL.

7. Select **+ Add Platform** to continue.

8. Select Platform as **Website**.

9. Insert your website at **Site URL** and click **Save Changes**.

10. Next page, set the **Status** as **On**.

11. **Confirm** the setting.

12. Look for **App Secret**, and select **Show**.

13. Facebook API management page will display **App ID** and **App secret**.

14. Go to website editor -> Site -> System Pages -> Login, click on Login form to open Login setting, to enable Facebook Login Setup.

    1. Select facebook tab.
    2. Insert App ID for Facebook Client ID and App Secret for Facebook Client Secret.
    3. Click OK to add these values to your form.

    ![image](images/register_and_login/img_facebook_login_01.png)

    4. On Login Setting, click open switch button.
    5. Click "Preview"
    6. Click "Save" to save all of your setting above.

    ![image](images/register_and_login/img_facebook_login_02.png)

15. The Facebook Login single sign-on is available for your user to login to your website without make a new register.
