<div align=center>

<h1>tapio-auth-basic</h1>

</div>

This is a reference implementation of **Basic Authentication with AuthorizationKey** against the tapio APIs (Tadamo, Maintenance Service).  
AuthorizationKeys are generated from tapio add-ons (ERP, Measurement Systems, ToolManager Office) and can be used to access APIs without registering separate Azure AD applications.

Further reading:

- [HTTP Basic Authentication (RFC 7617)](https://datatracker.ietf.org/doc/html/rfc7617)  

---

## 🚀 Available Samples

This repository contains sample projects showing how to call tapio APIs using Basic Auth.

### Sample Location

The authentication samples can be found in:

- **Source Code:** `Source/Tapio.Authentication/Tapio.Authentication/AuthenticationSamples.cs`
- **Documentation:** `Source/Tapio.Authentication/Tapio.Authentication/README.md`

### Each sample demonstrates

- How to configure the AuthorizationKey with Subscription Id and Application Id
- How to send requests to Tadamo and Maintenance Service APIs
- How to handle common errors (401 Unauthorized, 403 Forbidden)
- Proper error handling patterns for different API clients

### Getting Started

1. Obtain your Subscription Id, Application Id, and Authorization Key from [my.tapio.one](https://my.tapio.one)
2. Review the sample code in `AuthenticationSamples.cs`
3. Follow the detailed setup instructions in the documentation

For detailed authentication setup instructions, see the [Authentication Documentation](Source/Tapio.Authentication/Tapio.Authentication/README.md).
