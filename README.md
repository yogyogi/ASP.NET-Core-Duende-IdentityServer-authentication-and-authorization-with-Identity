# ASP.NET Core – Duende IdentityServer authentication and authorization with Identity
This is the implementation of Duende IdentityServer in ASP.NET Core app with ASP.NET Core Identity to provide authentication and authorization features. The complete tutorial is provided at - <a href="https://www.yogihosting.com/aspnet-core-duende-identityserver">Implement Duende IdentityServer</a>.

# Features
1. ASP.NET Core 8.0 version.
2. Server – ASP.NET Core app + Identity + Duende IdentityServer
3. ASP.NET Core Identity integration process
4. Duende IdentityServer integration process
5. Client – ASP.NET Core app with secured resource
6. Configure OpenID Connect (OIDC)
7. Showing the user login status
8. Testing the Duende Identity Server apps

# Getting Started
1. Simply Download the repository. You will get 2 projects - Server and Client. 
2. In the Server app perform migrations.
   
```sh
add-migration Migration1
Update-Database
```
3. From the Server app create a new Identity User.
4. Now run the Client App. Click the "Secure" link. You will be rediected to Duende IdentityServer for login. Perform login and access this page.

If any confusion see the tutorial whose link is provided at the top.

Don't forget to view the connection string of Identity Database given on `appsettings.json` file on "Server" app.

# User Interface
Here we can register a new Identity User.

<img src="https://www.yogihosting.com/wp-content/uploads/2024/05/register-duende-identityserver.png" alt="Register User"  title="Register User">

# Testing

Let's test the full working.

## Access Secure page

<img src="https://www.yogihosting.com/wp-content/uploads/2024/05/duende-is-authorization.png" alt="Secure Page"  title="Secure Page">

## Perform Login on Duende Identity Server

<img src="https://www.yogihosting.com/wp-content/uploads/2024/05/login-form-duende-is.png" alt="login feature"  title="Login Feature">

## View the Secure page

<img src="https://www.yogihosting.com/wp-content/uploads/2024/05/duende-identityserver-authorization.png" alt="View Secure Page"  title="View Secure Page">

In the secure page you will see the claims of the Logged in user.

## Support

Your support of every $5 will be a great reward for me to carry on my work. Thank you !

<a href="https://www.buymeacoffee.com/YogYogi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="200"  style="height: 60px !important;width: 200px !important;" ></a>
<a href="https://www.paypal.com/paypalme/yogihosting" target="_blank"><img src="https://raw.githubusercontent.com/yogyogi/yogyogi/main/paypal.png" alt="Paypal Me" width="300"></a>
