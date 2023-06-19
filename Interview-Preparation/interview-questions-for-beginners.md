# Interview Questions<b>

<details>
 <summary> <b> Beginner Level Questions :computer: </b>  </summary>
  
  1. What is a Cloud? 
  
  2. Explain various cloud service models.
  
  3. Explain various cloud deployment models.
  4. Explain difference between Google Cloud, Google Cloud Platform and GSuite.
  5. Explain GCP Global Infrastructure terminologies: Region, Availability Zone
  6. Explain Regional services vs Global Services 
  7. Explain Regional Resources vs Global Resources vs Zonal Resources
  8. How pricing works with Google Cloud Platform services? | Billing Account
  9. What is GCP CloudShell and when to use?
  10. What is GCP SDK? 
  11. Explain GCP Resource Hierarchy.
  12. What is a GCP Resource and GCP Resource Manager
  13. What are Resource Labels? 
  14. What is the difference between GCP Resource Labels and Tags? With atleast 2 use-cases
  15. <a href="https://cloud.google.com/compute/docs/faq#virtualcpu">What is a virtual CPU in Compute Engine? </a>
  16. <a href="https://cloud.google.com/compute/docs/faq#app_engine_gce">How do App Engine and Compute Engine relate to each other?? </a>
  17. <a href="https://cloud.google.com/compute/docs/faq#how_does_pricing_and_purchasing_work">How does pricing works for GCE? </a>
  18. <a href="https://cloud.google.com/compute/docs/faq#what_are_service_accounts">What are Service Accounts and when to use it? </a>
  19. <a href="https://cloud.google.com/compute/docs/faq#how_do_i_find_out_how_much_quota_i_have_used_or_have_left"> How do I find out how much quota I have used or have left? </a>
  20. <a href="https://cloud.google.com/compute/docs/faq#what_are_preemptible_vm_instances_and_how_are_preemptible_instances_different_than_normal_instances">What are Preemptible VM instances, and how are Preemptible instances different than normal instances?</a>
  21. <a href="https://cloud.google.com/compute/docs/faq#can_i_attach_my_persistent_disk_to_more_than_one_instance">Can I attach my persistent disk to more than one instance? </a>
  22. <a href="https://cloud.google.com/compute/docs/faq#when_should_i_use_persistent_disks_versus">When to use Persistent Disk vs Cloud Storage? </a>
  23. <a href="https://github.com/GoogleCloudPlatform/guest-agent/#metadata-scripts">What are Startup and Shutdown scripts in Google Compute Engine? Explain atleast 2 use-cases </a>
  24. How would you achieve high availability for Compute Engine hosted application?
  25. How would you enable auto-scaling for application hosted on Compute engine instance?
  26. How would you provision more than one Compute Engine instance? Explain all the possible ways.
  27. Explain different pricing options available for Compute Engine.
  28. How would you deploy an application on Google App Engine? Recommended practice?
  29. How many maximum number of App Engine Instance we can host per Project?
  30. What are the runtimes (programming languages) does Google App Engine supports? (Go | PHP | Java | Python | Node.js | Ruby | .NET)
  31. What is Google Kubernetes Engine? Explain about Data plain and Control plain components. </br>
  Google Kubernetes Engine is a powerful cluster manager and orchestration system for running Docker containers. It is designed to make it easy to deploy and manage containerized applications at scale. </br>
  32. How does the scheduling of workloads happen in GKE? </br>
  Workloads in GKE are scheduled using the Kubernetes scheduler. The scheduler looks at the resources that are required by each workload and then tries to find the best place to run it based on available resources. </br>
  33. Can you explain what a *Pod* is in the context of GKE? Explain some key features of Pod with one real world example.</br>
  A pod is a group of one or more containers that are deployed together on a single node in a Google Kubernetes Engine cluster. Pods are the smallest deployable units in GKE and are used to encapsulate and isolate application containers.</br>
  35. What is a deployment controller? Explain with example.</br>
  A deployment controller is a type of controller that is responsible for creating and managing deployments in a Google Kubernetes Engine cluster. A deployment controller can be used to create and manage both new deployments and existing deployments.</br>
  35. How would you configure load balancing for your application running on GKE cluster?</br>
  You can configure load balancing for your application running on GKE by creating a LoadBalancer Service object. This will create a Google Cloud Load Balancer that will distribute traffic evenly across the pods in your deployment.</br>
  37. When should you use persistent volumes in GKE cluster?</br>
  You should use persistent volumes in GKE when you need to store data that needs to be persisted even if the pod is deleted. For example, if you are running a database in a pod, you will want to use a persistent volume so that the data is not lost if the pod is deleted.</br>
  38. What’s the difference between ephemeral storage and persistent disk storage in GKE cluster?</br>
  Ephemeral storage is a type of storage that only lasts for the duration of a single pod’s lifetime. This means that any data stored in ephemeral storage will be lost when the pod is deleted. Persistent disk storage, on the other hand, is designed to be long-term storage that can outlast the lifetime of a single pod. This makes persistent disk storage a better option for storing data that needs to be preserved even if the pod is deleted.</br>
  39. What are some important configurable parameters that can affect the performance of your containerized applications running on GKE?</br>
      - *Number of replicas*: This parameter determines how many copies of your application will be running. More replicas will generally mean better performance, but it also depends on your application and how it scales.

      - *CPU and memory limits*: These parameters determine the maximum amount of resources that your application can use. If your application exceeds these limits, it may be throttled or even killed.
      - *The Image*: The base image that your application is built on can also affect performance. For example, using a lightweight image like Alpine Linux can help improve performance</br>
  40. Can you give me some examples of real-world applications that use Google Kubernetes Engine? </br>
      - Netflix, Etsy, The New York Times, Spotify, Ubisoft </br>
      
  41. What is a cluster and how does it relate to GKE?</br>
  A cluster in GKE is a group of Compute Engine instances that you can manage as a single unit. Clusters can range in size from a single instance to thousands of instances. You can use clusters to improve the availability and performance of your applications.</br>
  
  42. Where does GKE store node configuration data? </br>
  GKE stores node configuration data in JSON files called “config maps.” These config maps are stored in a GKE-specific location in Google Cloud Storage (GCS).</br>
  
  43. What is a master node and how does it differ from other types of nodes in GKE?</br>
  A *Master node* in GKE cluster is responsible for managing the cluster and all of the workloads running on it. Other types of nodes in GKE include worker nodes, which are used to run applications and services, and infra nodes, which are used to manage and monitor the cluster.</br>
  
  44. What happens if a node goes down while running containers on GKE? Is there any way to prevent this from happening?</br>
  If a node goes down while running containers on GKE, the containers will be automatically restarted on another node in the cluster. There is no way to prevent this from happening, but it is not typically a cause for concern as the containers will be quickly restarted on another node. </br>
  
  45. 
</details>
<details>
 <summary> <b> Intermediate Level Questions ⚙️ </b>  </summary>
  
</details>
<details>
 <summary> <b> Expert Level Questions :gem: </b>  </summary>
  
 </details> 
