# PreAuthorize_Roles_Spring

First run the sql files in sql folder.
Using these preAuhorze annotaion,we can completely remove role access configuration in Websecurityconfig and configure them directly on controller/services/repo.

The whle project is about to haveing 2 apis,get and post. 
There are 2 users one is admin,other is user.So the Roles are created for the users.

Now we configure the websecurity adapter so that
 1. Only Admins can use post
 2. Both Admins and users can use GET
 
 User Logs in with email and pasword
