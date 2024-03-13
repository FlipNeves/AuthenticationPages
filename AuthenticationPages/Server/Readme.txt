AuthenticationPages

Description:
This project serves as a simple demonstration of authentication with Google. By following the documentation provided by Microsoft, you can easily set up and test authentication functionalities.

Setup:
To build and run the project, just follow these steps:

1. Navigate to the provided Microsoft documentation: [Google Logins with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/social/google-logins?view=aspnetcore-8.0).
2. Obtain your Google credentials and ensure you have the required permissions.
3. Manage the User Secrets in file named "secrets.json" in the project.
4. Inside "secrets.json", add your Google client ID and client secret in the following format:

{
  "Authentication:Google:ClientId": "<clientId>",
  "Authentication:Google:ClientSecret": "<clientSecret>"
}


Normal and base Readme.txt:
This code includes a dependency on Duende IdentityServer.
This is an open source product with a reciprocal license agreement. If you plan to use Duende IdentityServer in production this may require a license fee.
To see how to use Azure Active Directory for your identity please see https://aka.ms/aspnetidentityserver
To see if you require a commercial license for Duende IdentityServer please see https://aka.ms/identityserverlicense
