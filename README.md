# Netskope Admin SSO Control for Firefox
A Mozilla Firefox extension that manages and controls automatic redirection to Single Sign-On (SSO) for the Netskope Administrator Portal.

This extension is particularly useful for administrators who manage multiple Netskope tenants. It prevents automatic redirection to SSO, allowing login with a local administrator account instead. Users can configure which tenants should redirect to SSO and which should open the local account login page (`https://example.goskope.com/locallogin`).

## Usage
1. Download and install the [Firefox extension](Netskope%20Admin%20Portal%20SSO%20Control.xpi).  
2. Visit a Netskope Administrator Portal with SSO enabled. The extension will automatically redirect you to the local login page instead of initiating the SSO process.  

If you’d like to allow SSO redirection for specific tenants, you can add exceptions in either of the following ways:  
- Click the extension icon and manually add the Netskope tenant FQDN as an exception.  
- While viewing the Netskope Administrator Portal in the active browser tab, click the extension icon and select **Add Current FQDN and Refresh**.  


## Demo
https://github.com/user-attachments/assets/54523e5e-f653-4a81-ae9d-1c94c1c8a19d

## Known Issues
- The extension cannot currently handle directly accessing a non-login page for the Netskope Administrator Portal, e.g., clicking a saved bookmark for **Advanced Analytics** will still redirect to SSO.
