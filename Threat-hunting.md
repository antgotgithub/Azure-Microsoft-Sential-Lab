

Added the **Entra ID** connector and created a hunt to detect user creation and deletion events.

I built **two KQL queries** for the hunt:  
* **New User Detected**  
* **User Deleted**

<p float="left">
  <img src="images/new.png" alt="Entra ID Hunt Overview" width="500"/>
</p>

To validate the queries, I **created and then deleted a test user** in Entra ID.

<p float="left">
  <img src="images/new2.png" alt="KQL Queries for New and Deleted Users" width="500"/>
  <img src="images/new3.png" alt="Test User Creation and Deletion" width="500"/>
</p>

Confirmed that both queries returned the expected results:

<p float="left">
  <img src="images/new4.png" alt="Query Results – New User" width="500"/>
  <img src="images/new5.png" alt="Query Results – User Deleted" width="500"/>
</p>
