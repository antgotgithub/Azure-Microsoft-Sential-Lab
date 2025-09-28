# Entra ID Hunt: User Creation and Deletion

Added the **Entra ID** connector and created a hunt to detect **user creation** and **user deletion** events.

<p float="left">
  <img src="images/new.png" alt="Entra ID Hunt Overview" width="500"/>
</p>

Created **two KQL queries** for the hunt:  
* **New User Detected**  
* **User Deleted**

To validate the queries, a **test user** was created and then deleted in Entra ID.

<p float="left">
  <img src="images/new2.png" alt="KQL Queries for New and Deleted Users" width="500"/>
  <img src="images/new3.png" alt="Test User Creation and Deletion" width="500"/>
</p>

Both queries successfully returned the expected results:

<p float="left">
  <img src="images/new4.png" alt="Query Results – New User" width="500"/>
  <img src="images/new5.png" alt="Query Results – User Deleted" width="500"/>
</p>
