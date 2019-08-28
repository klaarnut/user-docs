# Register and Login System

To​ allow​ website​ visitor​s​ to​ register​ in​ your​ website​ as​ a​ member for​ purpose such​ as​ some​ privilege page​ access​ or​ some​ part​ of​ website​ admin​ interface for​ some​ exclusive​ users,​ you can​ activate​ the​ Built-in Login​ System​ to​ allow​ users to​ use​ their​ current​ account​ from​ Google​ Email, Facebook, Twitter, and​ also​ the​ dorect register​ with​ their​ email​ address​ is​ support​ed. 
## Activate Google for register and login system

Google Login Setup for Built-in Channels in your website

Google Login Setup for Built-in Channels requires Google API Setup . If you don't setup it yet, please go setup by the guide first. If you did it already, you can continue to number 2.

After the Google API setup is completed, go to https://console.developers.google.com to select project you created for your website.

Click Library.

Search for Google+ API.

Enable Google+ API (Google+ API should be already enabled by setting Google API for Marketing (number 1). But if it’s not, just enable it again.)

At Google Developer Console page, click Credentials.

Select OAuth Client ID you created from number 1.

Google Developer Console page will display Client ID and Client secret.

Login as admin to your website.

Go to website editor -> Site -> System Pages -> Login, click on Login form to open Login setting. Enable Google Login Setup.

Insert Client ID and Client secret from number 8 to Google Login Setup, and click OK to complete setting.
 

If Google Login returns error when visitors try to login, please contact your host provider to allow google rule_id in ModSecurity by this guide. 
