# Web Request Journey

## Website
YouTube

## About the Project

This project explains what happens when I type `youtube.com` in my browser and press Enter.

It follows the request from the client to YouTube's infrastructure and explains how the response comes back to the browser.

## Request Journey (Hops)

The main steps are:

1. **The Client (Browser):** The user enters the URL or triggers an action, and the browser initiates the HTTP request.
2. **DNS Resolution:** DNS translates the domain name (`www.youtube.com`) into a machine-readable IP address.
3. **Network & Infrastructure:** The request travels through routers, switches, and the internet until it reaches YouTube's infrastructure.
4. **Server Processing & Response:** YouTube's server processes the request and sends a response back (e.g., in the Network tab, we observe background `Fetch/XHR` requests like `log_event?alt=json` returning a **Status Code: 200 OK**).
5. **Rendering:** The browser receives the response data, headers, and content, and displays the page to the user.

## Diagram

The diagram below shows the journey of the request.

<!-- The diagram will be added here later. -->  <img width="742" height="167" alt="image" src="https://github.com/user-attachments/assets/aa4ff815-6397-462f-8951-8c3f59805790" />


