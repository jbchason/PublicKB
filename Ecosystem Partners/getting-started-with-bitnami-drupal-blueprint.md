{{{
  "title": "Getting Started with Drupal - Blueprint",
  "date": "04-21-2015",
  "author": "Bob Stolzberg / Bitnami",
  "attachments": [],
  "contentIsHTML": false
}}}

![Drupal Logo](https://bitnami.com/assets/stacks/drupal/img/drupal-stack-220x234.png)

### Technology Profile

Drupal is one of the most versatile open source content management systems on the market. Over a thousand developers contributed to the code in the most recent version. Drupal is built for high performance and is scalable to many servers, has easy integration via REST, JSON, SOAP and other formats, and features a whopping 15,000 plugins to extend and customize the application for just about any type of website. You won't feel alone if you use Drupal; the hundreds of thousands of Drupal users around the world have built a very robust community with local meetups and global user conferences.

### Description

Through the CenturyLink Blueprint integration, Bitnami Drupal Stack provides a click-through solution to install and configure Drupal on the Linux platform.

For more information, please visit [Drupal.org](http://drupal.org)

### Audience
CenturyLink Cloud Users

### Impact
After reading this article, the user should feel comfortable getting started using the Bitnami Blueprint technology on CenturyLink Cloud.

### Prerequisite
- Access to the CenturyLink Cloud platform as an authorized user.
- Existing Linux server and access

### Postrequisite
- If you want to access your application over the internet, please perform the following tasks after you receive an email notifying you that the Blueprint completed successfully:

1. If you need to connect to your server via the Internet, [Add a Public IP](../Network/how-to-add-public-ip-to-virtual-machine.md) to your server through Control Portal

2. [Allow incoming traffic](../Network/how-to-add-public-ip-to-virtual-machine.md) for desired ports by clicking on the Servers Public IP through Control Portal

### Install Bitnami Drupal Stack on Linux Blueprint
1. Locate the Bitnami Drupal Stack Blueprint
  1. Starting from the CenturyLink Control Panel, navigate to the Blueprints Library.
  2. Search for “Drupal” in the keyword search on the right side of the page.
  3. Locate the 'Install Bitnami Drupal on Linux' Blueprint

2. Choose and Deploy the Blueprint. Click the “Install Bitnami Drupal on Linux” Blueprint.

3. Configure the Blueprint. Complete the information below:
  1. Execute on Server: Select a Linux x64 server to deploy the Blueprint on.
  2. Apache Web Server Port, e.g. 80
  3. SSL Port, e.g. 443
  4. Web Server domain, e.g. 127.0.0.1
  5. MySQL Server port, e.g. 3306
  6. Login, e.g. user
  7. Your real name, e.g. User Name
  8. Email Address, e.g. user@example.com
  9. Password
  10. Do you want to configure mail support?, e.g. 0
  11. Default email provider:, e.g. custom
  12. SMTP User
  13. SMTP Password
  14. SMTP Port
  15. SMTP Host
  16. Secure connection, e.g. tls

4. Review and Confirm the Blueprint.
  1. Click “next: step 2”
  2. Verify your configuration details.

5. Deploy the Blueprint.
  1. Once verified, click on the ‘deploy blueprint’ button. You will see the deployment details along with an email stating the Blueprint is queued for execution.
  2. This will kick off the blueprint deploy process and load a page to allow you to track the progress of the deployment.

6. Monitor the Activity Queue.
  * Monitor the Deployment Queue to view the progress of the blueprint.
  * You can access the queue at any time by clicking the Queue link under the Blueprints menu on the main navigation drop-down.
  * Once the blueprint completes successfully, you will receive an email stating that the blueprint build is complete. Please do not use the application until you have received this email notification.

### Access your Drupal server
After your Blueprint deploys successfully, please follow these instructions to access your server:

  1. Check email to obtain Server Name and IP Address Login information
  2. Log in to the server and start having fun!

### Pricing
The costs associated with this Blueprint deployment are for the CenturyLink Cloud infrastructure only.  There are no Bitnami license costs or additional fees bundled in.

### About Bitnami
CenturyLink Cloud works with [Bitnami](http://www.bitnami.com) to provide open source software integrations to its customers.  Bitnami is a library of popular server applications and development environments that can be installed with one click, either in your laptop, in a virtual machine or hosted in the cloud. Bitnami takes care of compiling and configuring the applications and all of their dependencies (third-party libraries, language runtimes, databases) so they work out-of-the-box. The resulting packaged software (a 'stack') is then made available as native installers, virtual machines and cloud images. These Bitnami application packages provide a consistent, secure and optimized end-user experience when deploying any app, on any platform.

### Frequently Asked Questions

- #### Who should I contact for support?
- For issues related to deploying the Bitnami Blueprint on CenturyLink Cloud, Licensing or Accessing the deployed software, please visit the [Bitnami Support website](http://www.bitnami.com/support)
- For issues related to CenturyLink Cloud infrastructure (VM’s, network, etc), please open a CenturyLink Cloud Support ticket by emailing noc@ctl.io