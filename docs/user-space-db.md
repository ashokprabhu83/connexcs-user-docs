# User Space Database

A user database is a flexible datastore that has multiple use cases mainly used in allocations that you can build using ScriptForge. It is also available in three(3) different backends, each with their own advantages and disadvantages:

1. **High Capacity** - This is a key-value pair store that uses eventual consistency to replicate between zones. Ideally, it is used for lists of numbers, such as DNC lists. It should not be used for counters or higher-speed writes.

2. **High Speed** - This operates as a caching layer, is exceptionally fast, and is also eventually consistent between zones. It should be considered ephemeral, and used like a cache.

3. **Highly Consistant** - This datastore benefits from a global truth, it is fast at reads, slower on updates, and is not designed to hold large quantities of data (less than 10,000 records).

When you create your datastore, you can specify which type will be created. Datastores can be used for checking a list of numbers, caching external lookups, or creating stateful applications that allow users a certain amount of free minutes per month.

To set up a User Space Database. 
1. Go to **Setup** > **User Space Database** from the dashboard. 

![alt text][user-space-img-1]


2. Click the **`+`** button.

![alt text][user-space-img-2]

3.	Fill the details in the dialogue box.

4.	Click the **`Save`** button. 

![alt text][user-space-img-3]

**Refresh the list**

Press the **`Refresh`** button to see an updated list of items. This is the best way to make sure you're working with the most recent sets of data.

![alt text][user-space-img-1a]

**Deleting Items**

To delete an item from the list:

1. Select any name from the **Area** column.
2. Click the **`delete`** button.

![alt text][user-space-img-2a]


## Edit the Details

To edit the details of any item:

1. Click on name of the **Area** column.

![alt text][user-space-img-4]

1. Edit the details in the dialog box, like creating a new datastore.
2. Click the **`Save`** button.

![alt text][user-space-img-5]

## Searching Text Fields

You can search the _Area_ and _Key_ from the search text fields using the search box at the top right.

![alt text][user-space-img-6]

[user-space-img-1]: /developers/img/185.png "user-space-img-1"
[user-space-img-2]: /developers/img/186.png "user-space-img-2"
[user-space-img-3]: /developers/img/187.png "user-space-img-3"
[user-space-img-1a]: /developers/img/188.png "user-space-img-1a"
[user-space-img-2a]: /developers/img/189.png "user-space-img-2a"
[user-space-img-4]: /developers/img/190.png "user-space-img-4"
[user-space-img-5]: /developers/img/191.png "user-space-img-5"
[user-space-img-6]: /developers/img/192.png "user-space-img-6"
