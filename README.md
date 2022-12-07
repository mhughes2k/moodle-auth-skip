Moodle Skip Authentication Plugin
=================================

This authentication plugin allows you set up a user that you will 
be logged in as, without need to specify a user name or password.

This is created for use by developers who may have to switch between
different accounts frequently whilst developing, and saves them the
hassle of having to interactively log in each time.

This plugin will **only** work if Debug mode is set to DEVELOPER.

How to Use
----------
1. Install plugin.
2. Goto Auth Plugins configuration page
3. Enable "Auto Admin Login"
4. Move "Auto Admin login" to top of list.
5. Go to "Debugging" settings
6. Set Debugging to DEBUG_DEVELOPER (required).

Access your server and click a login link and you should be automatically logged
in as the admin user for your server.