<div align=center>

<h1>tapio-samples</h1>

</div>

This repository contains code samples and reference implementations demonstrating how to integrate with various tapio APIs and services. The samples cover different aspects of tapio development including authentication methods, API usage patterns, and integration best practices.

---

## 🚀 Available Samples

This repository contains sample projects showing different ways to work with tapio APIs and services.

### Authentication Samples

Learn how to authenticate with tapio APIs using different methods:

- **Basic Authentication with AuthorizationKey** - Reference implementation for APIs like Tadamo and Maintenance Service
  - **Source Code:** `Source/Tapio.Authentication/Tapio.Authentication/AuthenticationSamples.cs`
  - **Documentation:** `Source/Tapio.Authentication/Tapio.Authentication/README.md`

AuthorizationKeys are generated from tapio add-ons (ERP, Measurement Systems, ToolManager Office) and can be used to access APIs without registering separate Azure AD applications.

#### Authentication Sample Features

- How to configure the AuthorizationKey with Subscription Id and Application Id
- How to send requests to Tadamo and Maintenance Service APIs
- How to handle common errors (401 Unauthorized, 403 Forbidden)
- Proper error handling patterns for different API clients

#### Getting Started with Authentication

1. Obtain your Subscription Id, Application Id, and Authorization Key from [my.tapio.one](https://my.tapio.one)
2. Review the sample code in `AuthenticationSamples.cs`
3. Follow the detailed setup instructions in the documentation

For detailed authentication setup instructions, see the [Authentication Documentation](Source/Tapio.Authentication/Tapio.Authentication/README.md).

### Future Samples

This repository is designed to be extended with additional samples covering:

- Different tapio service integrations
- Advanced API usage patterns
- Best practices for tapio development

---

## 📖 Further Reading

- [HTTP Basic Authentication (RFC 7617)](https://datatracker.ietf.org/doc/html/rfc7617)
