# Netskope Admin SSO Control for Firefox
A Mozilla Firefox extension that manages and controls automatic redirection to Single Sign-On (SSO) for the Netskope Administrator Portal.

This extension is particularly useful for administrators who manage multiple Netskope tenants. It prevents automatic redirection to SSO, allowing login with a local administrator account instead. Users can configure which tenants should redirect to SSO and which should open the local account login page (`https://example.goskope.com/locallogin`).

## Known Issues
- The extension cannot currently handle directly accessing a non-login page for the Netskope Administrator Portal, e.g., clicking a saved bookmark for **Advanced Analytics** will still redirect to SSO.
