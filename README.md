# GCP-Task

# Deploying WordPress using Google Kubernetes Engine

**In this project I am deploying WordPress site and connecting it to MySQL server for the database but wait this is not it , the real project is what's happening in the Back end.
In Back end I have used Google Load Balancer Services with Google Kubernetes Engine which empower my Website to handle a lot of traffic with zero down time and High scalability.**

So this is how i did it

* First thing we need to do is to create a Kubernetes Cluster.

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/K-1.PNG)

* Click on Create cluster and by giving simple information like name of your cluster, region and data center we can create the Cluster.

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/k-2.PNG)

* It may take few minutes. after it is done you will find a page like this

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/k-3.PNG)

* Now we need to connect to this kubernetes Cluster there are two ways to connect to the cluster
  1. First method is we can download kubernetes in our system and using the CLI of our system to connect to the cluster but this method is little difficult and time consuming.
  2. Simple way is just open cloud shell it has pre installed kubernetes you can directly get started with kubernetes.
* Now to connect with kubernetes click the connect button visible on the screen and click on run in cloud shell

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/k-4.PNG)

* To deploy our WordPress OS in our cluster

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/k-5.PNG)
![img1](https://github.com/adrsh-23/GCP-Task/blob/main/k-6.PNG)

* When it is successfully deployed we need to create Load Balancer
* Now even if we delete all pods, kubernetes will detect it and redeploy all the pods again. Let's try it

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/k-7.PNG)

* Create a MySQL instance

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/sql-1.PNG)

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/sql-2.PNG)

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/sql-3.PNG)

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/sql-4.PNG)

* And we are done, to check our site use Cluster Public IP to access the page

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/word-1.PNG)

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/word-2.PNG)

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/word-3.PNG)

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/word-4.PNG)

![img1](https://github.com/adrsh-23/GCP-Task/blob/main/word-5.PNG)

This confirms that our WordPress Setup is successful .

Thank You!!!




