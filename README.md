The **PeopleSoft Directory Viewer** functionality delivers front-end
functionality to manage files and directories on PeopleSoft servers for
end users.

The functionality consists of:

1.	Installation component where administrators can define the installation options available for different directories on the PeopleSoft Servers for end users.

2.	Setup component where administrators can define the permissions available for different directories on the PeopleSoft Servers for end users.

3.	Preferences component where users can define their personal preferences for the PeopleSoft server directory viewer.

4.	Viewer component where end users can manage files and directories on the PeopleSoft Servers.


**Common uses:**

The functionality is commonly used to:

The functionality is commonly used to: 
1.	Allow developers access to log files on the application server and web server for debugging errors and viewing integration logs.

2.	Allow end users the ability to upload and delete files to / from specific directories that can be used as upload directories for business transactions that require external files (csv / excel / etc.).

3.	Allow admins easy access for server directories while using the front-end application.


A word of caution: working with PeopleSoft servers means working with
the real server directories that are necessary to keep the PeopleSoft
environment running. Any file transaction that end users can perform
cannot be undone. **Delete is Delete!**

The functionality can safely be used in a production environment if and
when you have clearly defined which end users can perform which file
transactions in which directories.

**Overview Video:**

Check out the functionaliy via:

https://youtu.be/pnQKObe-csU

**Documents:**

1.  [Installation](installation_CY2_DIRECTORY_VIEWER.pdf)
2.  [Functional design and user manual](FD_CY2_DIRECTORY_VIEWER.pdf)
3.  [Technical design](TD_CY2_DIRECTORY_VIEWER.pdf)

