---
title: 'Vertex Setup'
description: 'This is a short step by step guide how to set up Gemini models through Google Vertex.'
---



1. Go to "Service Accounts" in the Google Cloud Console IAM Settings

<img src="/images/vertex-1.png"/>

2. Click on "Create Service Account"

3. Give the Service Account a name

<img src="/images/vertex-3.png"/>


4. Assign the "Vertex AI User" Role

<img src="/images/vertex-4.png"/>

5. Create the Service Account.

<img src="/images/vertex-5.png"/>

6. You are brought back to the Service Account overview.

<img src="/images/vertex-6.png"/>


7. On the overview page, click on "Manage keys"

<img src="/images/vertex-7.png"/>


8. Create a new JSON key

<img src="/images/vertex-8.png"/>


9. Download & open the JSON file

<img src="/images/vertex-9.png"/>

10. Copy the "private_key" attribute into the "API Secret" field in the Langdock Models page

11. Copy the "client_email" attribute into the "Endpoint" field in Langdock

12. Use a model ID from the Vertex portal (eg. `gemini-1.5-flash-001` or `gemini-1.5-pro-001`)
