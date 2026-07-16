# http-vs-https
# HTTP vs HTTPS

## Introduction

When we browse websites, use mobile applications, or communicate with web servers, data is transferred between a client (browser/app) and a server. This communication happens using protocols called **HTTP** and **HTTPS**.

Understanding the difference between HTTP and HTTPS helps us know how data is transferred securely over the internet.

---

# What is HTTP?

**HTTP (HyperText Transfer Protocol)** is a communication protocol used to transfer data between a client and a web server.

It defines how requests and responses are exchanged between a browser and a server.

### How HTTP Works

1. A user enters a website URL in a browser.
2. The browser sends an HTTP request to the server.
3. The server processes the request.
4. The server sends an HTTP response back to the browser.
5. The browser displays the requested content.

### Example

```
http://example.com
```

### Features of HTTP

- Transfers web pages, images, videos, and other resources.
- Works on the application layer of the OSI model.
- Uses port **80** by default.
- Faster compared to HTTPS because it does not perform encryption.
- Data is transferred in plain text.

---

# What is HTTPS?

**HTTPS (HyperText Transfer Protocol Secure)** is the secure version of HTTP.

It uses encryption to protect communication between a client and a server.

HTTPS uses **SSL/TLS certificates** to encrypt data and verify the identity of the website.

### How HTTPS Works

1. A user accesses a website using HTTPS.
2. The browser connects to the server.
3. The server provides an SSL/TLS certificate.
4. The browser verifies the certificate.
5. An encrypted connection is established.
6. Secure data transfer begins.

### Example

```
https://example.com
```

### Features of HTTPS

- Provides secure communication.
- Encrypts data between client and server.
- Prevents attackers from reading sensitive information.
- Uses port **443** by default.
- Requires an SSL/TLS certificate.

---

# Difference Between HTTP and HTTPS

| Feature | HTTP | HTTPS |
|---|---|---|
| Full Form | HyperText Transfer Protocol | HyperText Transfer Protocol Secure |
| Security | Not secure | Secure |
| Encryption | No encryption | Uses SSL/TLS encryption |
| Data Transfer | Data is sent as plain text | Data is encrypted |
| Port Number | Port 80 | Port 443 |
| Certificate | Not required | SSL/TLS certificate required |
| Protection | Vulnerable to attacks | Protects against data interception |
| Speed | Slightly faster | Slightly slower due to encryption process |
| Usage | Used for non-sensitive websites | Used for secure websites |

---

# Why Do We Use HTTP?

HTTP is used because it provides a standard way for clients and servers to communicate.

### Purpose of HTTP

- To transfer web resources between browsers and servers.
- To load websites and web applications.
- To send and receive information over the internet.
- To allow communication between frontend and backend systems.

### Examples of HTTP Usage

- Loading a simple website.
- Requesting images, files, and documents.
- Communicating with APIs.

---

# Why Do We Use HTTPS?

HTTPS is used to provide secure communication over the internet.

### Purpose of HTTPS

- Protect sensitive user information.
- Encrypt communication between client and server.
- Prevent unauthorized access to data.
- Verify that users are communicating with the correct website.

### Examples of HTTPS Usage

HTTPS is required for websites that handle:

- Login credentials
- Banking information
- Payment details
- Personal information
- Private messages

---

# Why HTTPS is Important?

Without HTTPS, attackers can perform attacks such as:

### 1. Data Interception

Attackers can capture information transferred between users and servers.

Example:

```
Username and password can be stolen during transmission.
```

### 2. Man-in-the-Middle Attack

An attacker can secretly intercept and modify communication between the client and server.

### 3. Data Protection

HTTPS ensures that transmitted data remains private and secure.

---

# HTTP and HTTPS in Real World

| Website Type | Recommended Protocol |
|---|---|
| Personal websites | HTTPS |
| Online banking | HTTPS |
| E-commerce websites | HTTPS |
| Social media platforms | HTTPS |
| Public information websites | HTTPS |

Today, almost all modern websites use HTTPS because security and privacy are essential.

---

# Summary

| HTTP | HTTPS |
|---|---|
| Transfers data without encryption | Transfers data with encryption |
| Less secure | Highly secure |
| Uses port 80 | Uses port 443 |
| No SSL/TLS certificate | Requires SSL/TLS certificate |
| Suitable for basic communication | Suitable for secure communication |

---

# Conclusion

HTTP is the foundation of communication on the web, but it does not provide security. HTTPS improves HTTP by adding encryption and authentication using SSL/TLS.

For modern websites and applications, HTTPS is preferred because it protects user data, builds trust, and provides secure communication over the internet.