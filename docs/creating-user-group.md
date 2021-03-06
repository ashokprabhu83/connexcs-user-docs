# Creating a User Group 

You can create a user group in the ConnexCS Control Panel, when you want to assign a specific set of access permissions to the features in the Control Panel, to multiple users. Typically, you create user groups to assign permissions depending on the roles that the users play in your Carrier Service business model. 

For example, the Network Services Engineers need permissions to set up routing and not the customers' billing details. Similarly, the Billing team needs permissions to access and modify the customers' billing details and not to set up routing for customers' calls. 

!!! question "How does the permissions model work in the ConnexCS Control Panel?" 
    You should specify an email address you use often, because:
    
    * The permissions model in the ConnexCS Control Panel consists of Global permissions and Granular permissions.
    *	The Global and Granular permissions are categorized as follows - Create, Read, Update, and Delete (CRUD) permissions for the features in the ConnexCS Control Panel.
    * The Granular permissions override and nullify all the Global permissions. For example, if you assign all of the CRUD permissions globally, and assign granular Read permissions to 3 features, the group has permissions to read data for only 3 features. 
    * If you do not assign granular permissions to a group, the group has permissions to use all features in the ConnexCS Control Panel, depending on the level of global permissions (CRUD). For example, if you assign only Create and Read permissions globally, the group has permissions to create and read data for all features.

To create a user group:

1.  Log into the ConnexCS Control Panel.
	 
    ConnexCS displays the page you were on when you logged out of the Control Panel.
    
2.  Click `Setup > Settings > User` in the navigation panel (located on the left of the page).
    
    The Users and Groups page appears.
    
    You can see the list of users on the left of the page, and the list of groups on the right of the page. 

3.  Click the '+' icon (located on the left of the page).
    
    The User pop-up appears.
    
4.  Do the following to create a user group:
    
    * In the `Name` text box, enter the name of the user group.
       
    * 	From the `Default Permission` list box, select the level of global permissions that this group must have.
    
    	The options available are: `Create`, `Update`, `Read`, and `Delete`. By design, all of Create, Update, Read, and Delete permissions are selected. 
	
	You can repeat this step multiple times, if you want to associate the user with multiple user groups. For more information about how to create a user group, see <link to user group topic>.
    
    *	(Optional) To delete a permission, click `X` located at the right of a permission. 
    
    * 	To add a permission, click the down arrow at the right of the list box and click the permission.
    
5.  Click `Save`.
	
    ConnexCS Control Panel confirms that it has created a new IVR setup.
	
    You can see an entry for the new IVR setup on the IVR page.
    
6.  (Optional) To abort creating the IVR setup, click `X` located at the top-right corner of the pop-up.

7.  Do the following to create a user group:
    
    *	Click the name of the user group, on the Users and Groups page. 
    
    	The Group pop-up appears. You will see an Add Group Permission table on the pop-up.
    	
    *	Click the `+` icon (located on the right of the pop-up).
	
	The Group Permission pop-up appears. 

    *	From the `Area` drop-down list, select the functional area of the permission. 
    
    	For example, Analytics, Carrier, Circuit-test, DID, Payment and so on. Scroll down the drop-down list to view all the functional areas.

    *	From the `Access` list box, select the permissions you want to assign.
    
    *	Click `Save`. 
        	    
    	ConnexCS Control Panel confirms that it has added the permissions.
	You can see an entry for the new permissions in the Add Group Permission table.
	You will see the following details for the permissions:
	
	*	Path - the path to the functional area's API;
	*	Access - the level of permissions;
	*	Action - the option to edit the functional area and the permissions.
	    
    *	(Optional) To abort adding the permissions, click `X` located at the top-right corner of the Group Permission pop-up.

8.  (Optional) Repeat step 7 to add more functional areas and more granular permissions.

	The following figure illustrates the Group pop-up with some granular permissions for the role of a Network Services Engineer.
	
	![alt text][groups-popup]
	
9.	(Optional) To edit a permission, click `Edit`, located in the Action column of the table, and change the `Area` and `Access` values of the permission.

10.	Click `Save`.

	ConnexCS Control Panel confirms that it has created a new IVR setup.
	
	You can see an entry for the new IVR setup on the IVR page.
    
11.	(Optional) To abort creating the IVR setup, click `X` located at the top-right corner of the pop-up.

[groups-popup]: /class5/img/groups-popup.png "groups-popup"
		

		 
