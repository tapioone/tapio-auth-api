<div align=center>

<h1>tapio-auth-basic</h1>

</div>

[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/tapioone/tapio-auth-api/CI/master)](https://github.com/tapioone/tapio-auth-api/actions)
[![GitHub](https://img.shields.io/github/license/tapioone/tapio-auth-api)](https://github.com/tapioone/tapio-auth-api/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/tapioone/tapio-auth-basic)](https://github.com/tapioone/tapio-auth-basic/issues)

This is a reference implementation of **Basic Authentication with AuthorizationKey** against the tapio APIs (Tadamo, Maintenance Service).  
AuthorizationKeys are generated from tapio add-ons (ERP, Kelch, ToolManager Office) and can be used to access APIs without registering separate Azure AD applications.

Further reading:

- [HTTP Basic Authentication (RFC 7617)](https://datatracker.ietf.org/doc/html/rfc7617)  
- [tapio API Documentation (coming soon)](https://developer.tapio.one)  
- [Homag Connect API docs (reference)](https://docs.homag.cloud/en/data-exchange/homag-connect/translate-to-english-connect-api)  

---

## 🔑 Authentication Example

Every request to a tapio API must include the `AuthorizationKey` in the `Authorization` header:

```http
Authorization: Basic <AuthorizationKey>
