# Install WordPress

 ## Move and unzip WordPress
 
 In the previous page, you downloaded WordPress. You should have the `wordpress.zip` file in your Downloads folder or some other location you were careful to note.

 Move `wordpress.zip` to `Applications > MAMP > htdocs` and double-click to unzip it.

 You can now safely move the `.zip` file to the Trash.

 ## Start up the MAMP Server

Launch MAMP, then go to MAMP Preferences > Web Server to tell MAMP where it should look for your WordPress files in order to serve them.

Select Applications > MAMP > htdocs > wordpress
 
Click to start the PHP and MySQL servers.

## Begin the WordPress installation process

Click “Open WebStart Page” from the MAMP application window.

Most users will want to choose "English" as their language.

**Stop here for now. Do *not* click "Let's go!"**

## Create a database

From the MAMP WebStart page in your browser, go to Tools > phpmyAdmin

In the left navigation, click “New” to create a new database.

You can name your database whatever you like, but it will be simplest to name it `wordpress`. Database names may not have spaces and should be all lower case.

Be sure that the *collation* you choose for your database is "utf8-general-ci". If that isn't the default choice find it in the dropdown menu and select it.

## Complete the WordPress installation

Return to the WebStart page in your browser. Click on “My Website.” Alternatively, you can simply type this URL into your browser's location bar:

`http://localhost:8888`

Like the URL for a site on the web, your local WordPress site lives at an address that begins with the `http` file transfer protocol. But since your local address isn't an address on the web, the protocal isn't followed by `www`. Instead it's followed by the default name of your computer's web host — "localhost" — and the port number on your computer from which the site is being served.

Click "Let’s go!"

Enter the *exact* name of the database you created in phpMyAdmin, probably `wordpress`.

Where it asks for a username, type `root`. Where it asks for a password, type `root` again.

Click "Run the installation".

## Set up your site

Give your site any name you want. You can always change it later.

Enter the username you'll use to log into your site.

Enter a password. Be sure to make note of it, or you'll find yourself locked out of your own site.

*Note:* These are the username and password for your site, not to be confused with the username and password you entered earlier (`root`, `root`). Those were the username and password for your *database.*

Enter your email address.

Click "Install WordPress".

Login with your user credentials.