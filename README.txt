1701 Industries website package

What is included
- index.html
- about.html
- projects.html
- partnerships.html
- contact.html
- styles.css
- script.js
- .nojekyll

Important note about the email address
The website includes working email links to hello@1701industries.com using mailto links.
However, the mailbox itself only becomes active after you create that mailbox with your email provider.
A website cannot create an email inbox on its own.

How to make hello@1701industries.com live with Namecheap
1. Log into Namecheap.
2. Open your domain.
3. Buy or activate Namecheap Private Email, or connect another email provider.
4. Create the mailbox hello@1701industries.com.
5. Make sure the MX records for your domain match the email provider instructions.
6. Test by sending an email to hello@1701industries.com.

How to upload to GitHub Pages
1. Create or open your GitHub repository.
2. Upload all files from this folder to the root of the repository.
3. In GitHub, go to Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select main branch and /root folder.
6. Save.

How to connect your Namecheap domain to GitHub Pages
In GitHub Pages:
1. Open your repository Settings > Pages.
2. Enter your custom domain.
3. Save.

In Namecheap Advanced DNS:
Add these A records for the root domain:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Add this CNAME for www:
- Host: www
- Value: aguycalledtaz.github.io

Wait for DNS propagation, then enable HTTPS in GitHub Pages.
