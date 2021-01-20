---
layout: page
title: Install Wordpress
---

## Make a Sandbox Directory

We are going to be installing a Wordpress site that will be hosted with your account at Reclaim Hosting. You will use this site over the semester as a "sandbox" in which you can install and learn new tools. First, we're going to create a new sub-directory in our cPanel in Reclaim Hosting database.

To create your sandbox:

- Log in to Reclaim Hosting with the account you created
- Go to `File Manager` and make sure you are in the `public_html` folder
- Add a new folder within your `public_html` folder called `sandbox` (make sure it says `public_html` under "New folder will be created in:")
- Navigate to the folder. It should be empty!

## Install a Wordpress Site

Rather than create your own professional website at the root directory for whatever domain name you chose, we're going to make a Wordpress website within your `sandbox` sub-directory. 

You are gong to follow these instructions to install a Wordpress site using Reclaim Hosting. But you are going to install it **within a specific sub-folder (sub-directory)** of your `sandbox` folder. The name of this sub-directory is going to be `website`. So when you're asked for Directory (Optional), type in: `sandbox/website`

Note: choose a username and password that you can remember and **copy/paste it somewhere for your reference.** This is what you're going to use to log in to this Wordpress site moving forward.

Instructions: <https://community.reclaimhosting.com/t/installing-wordpress/265>.

Now you should have a website installed under `http://yourdomainname/sandbox/website`. If you go back to Reclaim Hosting's `File Manager` and go back to `sandbox` folder, you should now see a new folder called `website`. If you look inside here, you will see a bunch of new folders and files that were automatically generated to "build" your Wordpress site. 

To actually start modifying your website, you need to log in to the Wordpress dashboard (separate from Reclaim Hosting). The login page will be: `http://yourdomainname/sandbox/website/wp-admin`, and you will use the username and password you specified when you installed Wordpress. Visit this URL and make sure that you are able to log in.

