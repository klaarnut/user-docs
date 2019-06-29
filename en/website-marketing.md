# Website Marketing

## Google API Setup

Once you setup [SEO and Meta tag](https://github.com/rvsitebuilder/user-docs/blob/7.1/en/easy-website-seo.md) for your website already. You can see website performance and how SEO works on Google Console.

Aside from loggin to Google Console, RVsitebuilder 7 can bring those report in your website admin area by setting Google API.

As above, to see your website report from Google Console, you can first set Google API with by this guide.

### Google API Setup

1. Register at https://console.developers.google.com/ 

2. In Google APIs page, click **Create** for setting your new Google API.

![image](images/mkt4.png)

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
3) Insert **Authorized JavaScript origins***
4.1) Insert **Callback URL for MKT Setting*** (Enter or click Create to add another field for 4.2)
4.2) Insert **Callback URL for Social Login***
*Please login to your website admin, go to Marketing -> Go to Setup to bring the value for inserting 3, 4.1 and 4.2.*
5) Don't forget to click **Save**.

![image](images/step8.png)

9. The **Client ID** and **Client Secret** are showing that you can copy before leaving this page by clicking **OK**.

![image](images/mkt12.png)

10. Once you clicked OK to leave OAuth client, at Google APIs page , select **Library**.

![image](images/mkt13.png)

11. Search for the following API setups to **Enable** them.

1) Analytics API
2) Google Analytics Reporting API
3) Google Search Console API
4) Google+ API
5) ite Verification API
*Sameple: Google Search Console API*

![image](images/mkt11.png)

*Click ***Enable*** to activate the API.*

![image](images/mkt11.2.png)

12. Login to your website admin, go to **Apps** -> **Marketing** -> **Go to Setup** to insert **Client ID** and **Client Secret** form number 9.

![image](images/webmkt1.png)

Then click **Create Google Authorization**.
*(You can find details from number 9 at Google API, menu Credential, click on the created project.)*

![image](images/mkt12.1.png)

![image](images/mkt12.2.png)

13. Once the detail are are successfully submitted, you will be leased to Google Login page.
Select account you want to use for Google Analytics setup for your website.

![image](images/18.png)

14. Allow Google to access by clicking **ALLOW**.

15. Once the setup completed, you will see **Google API Setup** page.

![image](images/20.png)

-------------------------------------------------------------------------