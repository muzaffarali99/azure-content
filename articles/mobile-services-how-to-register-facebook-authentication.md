<properties linkid="develop-mobile-how-to-guides-register-for-facebook-authentication" urlDisplayName="Register for Facebook Authentication" pageTitle="Register for Facebook authentication - Mobile Services" metaKeywords="Windows Azure Facebook, Azure Facebook, Azure authenticate Mobile Services" description="Learn how to use Facebook authentication in your Windows Azure Mobile Services app." metaCanonical="" services="" documentationCenter="" title="Register your apps for Facebook authentication with Mobile Services" authors=""  solutions="" writer="glenga" manager="" editor=""  />

# Register your apps for Facebook authentication with Mobile Services

This topic shows you how to register your apps to be able to use Facebook to authenticate with Windows Azure Mobile Services. 

<div class="dev-callout"><b>Note</b>
<p>To complete the procedure in this topic, you must have a Facebook account that has a verified email address and a mobile phone number. To create a new Facebook account, go to <a href="http://go.microsoft.com/fwlink/p/?LinkId=268285" target="_blank">facebook.com</a>.</p>
</div> 

1. Navigate to the <a href="http://go.microsoft.com/fwlink/p/?LinkId=268286" target="_blank">Facebook Developers</a> web site and sign-in with your Facebook account credentials.

2. (Optional) If you have not already registered, click **Apps** then click **Register as a Developer**, accept the policy and follow the registration steps. 

   	![][0]

3. Click **Apps**, then click **Create a New App**.

   	![][1]

4. Choose a unique name for your app, select **Apps for Pages**, click **Create App** and complete the challenge question.

   	![][2]

	This registers the app with Facebook 

5. Click **Settings**, type the domain of your mobile service in **App Domains**, then click **Add Platform** and select **Website**.

   	![][3]

6. Type the URL of your mobile service in **Site URL**, then click **Save Changes**.

	![][4]

7. Click **Show**, provide your password if requested, then make a note of the values of **App ID** and **App Secret**. 

   	![][5]

    <div class="dev-callout"><b>Security Note</b>
	<p>The app secret is an important security credential. Do not share this secret with anyone or distribute it with your app.</p>
    </div>

You are now ready to use a Facebook login for authentication in your app by providing the App ID and App Secret values to Mobile Services.  

<!-- Anchors. -->

<!-- Images. -->
[0]: ./media/mobile-services-how-to-register-facebook-authentication/mobile-services-facebook-developer-register.png
[1]: ./media/mobile-services-how-to-register-facebook-authentication/mobile-services-facebook-add-app.png
[2]: ./media/mobile-services-how-to-register-facebook-authentication/mobile-services-facebook-new-app-dialog.png
[3]: ./media/mobile-services-how-to-register-facebook-authentication/mobile-services-facebook-configure-app.png
[4]: ./media/mobile-services-how-to-register-facebook-authentication/mobile-services-facebook-configure-app-2.png
[5]: ./media/mobile-services-how-to-register-facebook-authentication/mobile-services-facebook-completed.png

<!-- URLs. -->
[Facebook Developers]: http://go.microsoft.com/fwlink/p/?LinkId=268286
[Get started with authentication]: /en-us/develop/mobile/tutorials/get-started-with-users-dotnet/
[Windows Azure Management Portal]: https://manage.windowsazure.com/
