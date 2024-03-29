# 01_oktaAuth


- Okta is a customizable, secure, and drop-in solution to add authentication and authorization services to your applications.
- we need to connect our application with Okta platform.
- Each time a user tries to authenticate, Okta will verify their identity and send the required information back to your app.
- Use our SDKs (software development kit) or API to connect your apps, add users, configure rules, customize your sign-in page,
  and then monitor your services from our built-in reports.


# what you can do with OKTA?


secure your frontend
- You can use Okta to allow your users to sign in with a username/password or with their social accounts, 
such as Google or Facebook using pre-built sign-in components from Okta. After the user has signed in, 
you can retrieve their user profile to customize the UI based on their role and apply your authorization
policies.

secure your api's
- You can use Okta to secure your APIs and application backends so that only authorized users and applications 
can call them. Define scopes, claims, and configure policies to determine who can have access to your API  
resources.

SSO - SINGLE SIGN ON
- single sign-on allows the user to log in once and access services without re-entering authentication factors.
Use Okta to allow your users to sign in to other applications instead of requiring them to remember separate 
sets of credentials for each application or service. Users can simply sign in once and access your full suite 
of applications.


Multi-factor authentication : when user try to access sensitive data.
- Use Okta to enable a second level of security (SMS, Email, Voice, Biometrics, Okta Verify, and so on) for
every sign in or configure policies to only enforce MFA based on location or network.


sign-in or redirect to any third party app
- Use Okta to allow users to sign in to the various internal and third-party applications using their existing
enterprise credentials or through Active Directory (AD) or LDAP servers.



SSO IMAGE
![image](https://github.com/Raksha-coder/01_oktaAuth/assets/72040957/8fe9cd3c-89c9-4cfc-a7dc-a977026d1a1e)


![image](https://github.com/Raksha-coder/01_oktaAuth/assets/72040957/8f6be2c3-8869-4c22-ad9f-e7741b1cd5a5)




# packages for okta

- okta.sdk
- microsoft.aspNetCore.Authentication.openIdConnect


# sign up on okta developer



# imp links

https://developer.okta.com/docs/guides/sign-into-web-app-redirect/asp-net-core-3/main/
https://developer.okta.com/blog/2019/04/10/build-rest-api-with-aspnetcore
https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc
https://developer.okta.com/docs/guides/sign-into-web-app-redirect/asp-net-core-3/main/
 
Need to check
https://developer.okta.com/blog/2019/04/10/build-rest-api-with-aspnetcore








