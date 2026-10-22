# Apple Corner World — Full-control starter prototype

## Features
- Customer-facing product listing, repair booking, repair lookup, contact and company announcements
- Demo owner dashboard to manage products, repair status, record sales and expenses, publish announcements, and export a JSON backup
- LRD and USD currency selection
- PWA manifest and service worker for installable-web-app support

## Publish online
Upload all files in this folder to the root of your GitHub repository, then go to Settings → Pages and enable deployment from the `main` branch and root folder. Open the URL GitHub provides on your phone.

## Android / Play Store
After the website is online over HTTPS, use https://www.pwabuilder.com/ to review packaging options, then follow current requirements in https://play.google.com/console/.

## Critical limitations
This remains a front-end prototype. It stores data in localStorage on the current browser/device only. Customers on other devices cannot see the same records, and the owner will not automatically receive requests. The demo code `2468` is visible in source and is NOT secure. No real payments are processed. Before public launch, replace the demo owner area with server-side authentication and an online database, set up backups, add a privacy policy and terms, and test security. Do not use this demo for sensitive customer data.
