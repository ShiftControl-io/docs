---
description: Start managing your organization quickly with ShiftControl
---

# Quickstart

### Trust JumpCloud in Google Workspace <a href="#trust-jumpcloud-in-google-workspace" id="trust-jumpcloud-in-google-workspace"></a>

If you use Google Workspace, the first thing you’ll need to do it trust the JumpCloud apps in your Google Workspace Admin interface.

This process is only required if an organization has their API Controls for Google Workspace Admin set to restricted, but we recommend following the process no matter what to ensure the apps are authorized.

{% hint style="info" %}
If the app doesn’t have the right permissions, you’ll receive a 400 error admin\_policy\_enforce ([Read more](https://jumpcloud.com/support/troubleshoot-google-workspace-integration#\_error\_400\_\_admin\_policy\_enforced\_)) when trying to approve the JumpCloud app during initial setup.
{% endhint %}

You can trust the JumpCloud apps in order to add them without having to lower the restrictions enforced.

The following apps will need to be approved/trusted:

<table><thead><tr><th width="154">App Name</th><th>Purpose</th><th>Identifier</th></tr></thead><tbody><tr><td>JumpCloud</td><td>Directory Sync of users and groups from JumpCloud</td><td>409100557052-up2bjo6c85fdvipudtkaqr7jqsesqnam.apps.googleusercontent.com</td></tr><tr><td>JumpCloud</td><td>Single Sign-On</td><td>629652647736-b7u1qe4oktmn7b6vnmdbabrd32lds4as.apps.googleusercontent.com</td></tr></tbody></table>

1. Login to the Google Workspace Admin Panel

Go to [https://admin.google.com](https://admin.google.com/), log in as an Admin.

2. Access the API Controls

Go to Security→Access and data control→API Controls.

3. Manage Google Services

Click on Manage Google Services.

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

4. View configured apps

In the middle card (Configured Apps), click on View list.

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

5. Add an OAuth App

Click on the Add App pulldown and select Oauth App Name or Client ID.

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

6. Search for each app

For each item in our list of apps to approve repeat steps 6 to 11. Enter the ID and hit search.

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

7. Select the app

Click Select on the App Name.

<figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

8. Select OAuth ID

Select the oAuth ID and hit Select.

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

9. Continue with all users

Choose “Your Org” (all users) and continue.

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

10. Trust the app

Select Trusted and Continue.

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

11. Finish

Click Finish.

<figure><img src=".gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

You have now trusted the apps that we’ll authorize to sync Google Workspace with JumpCloud.

### [​](https://docs.shiftcontrol.io/getting-started/quickstart#add-the-google-workspace-directory)Add the Google Workspace Directory <a href="#add-the-google-workspace-directory" id="add-the-google-workspace-directory"></a>

{% hint style="info" %}
This section is coming soon, we’re updating the process to make this easier!
{% endhint %}
