## Threat Intelligence and Azure Activity Integration

Once Sentinel is up and running, add the **Azure Activity** connection to monitor activity on Azure. Also add the **TAXII Threat Intelligence** connection.  

I used **PulseDive** below to ingest threat intelligence into Sentinel:

<p float="left">
  <img src="images/2.jpg" alt="PulseDive Threat Intelligence Ingestion" width="500"/>
</p>

Make sure your **threat intelligence** and **Azure activity logs** are coming in:

<p float="left">
  <img src="images/Taxii.png" alt="TAXII Threat Intelligence Logs" width="500"/>
  <img src="images/Azure.png" alt="Azure Activity Logs" width="500"/>
</p>

Next, download the **Entra ID connector**, add a user to the domain, and ensure the action is ingested into the logs:

<p float="left">
  <img src="images/4.jpg" alt="User Added to Entra ID" width="500"/>
  <img src="images/3.jpg" alt="Entra ID Logs Ingestion" width="500"/>
</p>
