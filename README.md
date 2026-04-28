# 🚀 Azure Secure Web Application Deployment

This project demonstrates how I deployed and secured a web application on Azure using App Service, custom domain, HTTPS, Azure Front Door, and WAF.

The main goal was to understand how real-world traffic flows through different Azure services, not just to deploy an app.

---

## 🌐 Overview

* Deployed a Flask web application on Azure App Service
* Connected a custom domain using Azure DNS
* Enabled HTTPS using App Service managed certificate
* Configured Azure Front Door for global routing
* Secured the application using Web Application Firewall (WAF)

---

## 🏗️ Architecture

User → DNS → Front Door → WAF → App Service → Flask App

---

## ⚙️ Implementation Summary

1. Deployed the application to Azure App Service
2. Verified the default Azure URL
3. Created DNS zone and configured domain records
4. Added CNAME and TXT records for validation
5. Bound custom domain to App Service
6. Enabled HTTPS using managed certificate
7. Created Azure Front Door and configured origin
8. Attached WAF for security
9. Configured routing and health probes
10. Updated DNS to route traffic through Front Door

---

## 🔐 Security

* HTTPS enabled for secure communication
* WAF enabled to protect against web attacks
* Traffic routed securely via Azure Front Door

---

## 📸 Documentation

A detailed step-by-step explanation with architecture and screenshots is available here:

project-documentation.pdf`


---

## 🌐 Demo Status

The application was deployed and tested successfully.

Resources are currently decommissioned to avoid unnecessary Azure costs.


## 🎯 Conclusion

This project helped me understand practical cloud architecture, DNS behavior, and secure traffic routing in Azure.
