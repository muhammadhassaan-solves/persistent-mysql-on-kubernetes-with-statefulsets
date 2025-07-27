<h1>Scalable and Persistent MySQL Deployment Using Kubernetes StatefulSets</h1>


<h2>Description</h2>
This project demonstrates the use of Kubernetes StatefulSets to run a reliable MySQL database. It includes persistent volume claims, headless services, and scaling behavior while ensuring data remains intact across pod restarts. <br />


<h2>Tools and Technologies</h2>


- Kubernetes
- StatefulSets 
- MySQL 
- PersistentVolumeClaims (PVCs)
- Headless Service
- kubectl 
- YAML 
- StorageClass

<h2>Project Walk-through</h2>

<p align="center">
Set Up Headless Service & Configure StorageClass
<br />
<img src="https://i.postimg.cc/0NFBw9jr/1.jpg"/>
<br />
<br />
Deploy MySQL StatefulSet <br/>
<img src="https://i.postimg.cc/gcvTxFWk/2.jpg" />
<br />
<br />
Test Data Persistence 
<br/>
<img src="https://i.postimg.cc/gJbKpjry/3.jpg"/>
<br />
<br />
Scale StatefulSet <br/>
<img src="https://i.postimg.cc/8cKW7zk0/4.jpg" />
<br />
<br />
Patch (Update) the StatefulSet <br/>
<img src="https://i.postimg.cc/T27WqhGk/5.jpg" />
<br />
<br />
Check Pod DNS and Connectivity <br/>
<img src="https://i.postimg.cc/FHcd4ZSq/6.jpg" />
<br />
<br />
</p>

