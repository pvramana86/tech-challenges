Challenge #1

A 3-tier environment is a common setup. Use a tool of your choosing/familiarity create these resources. Please remember we will not be judged on the outcome but more focusing on the approach, style and reproducibility.

3-tier IaaS Solution :

Overview :
The Solution includes Web Servers, Application Servers and Database Servers.Following best practices for running a 3 tier common environmrnt setup in Cloud/on-perm given Architecture model will help to achive the build/setup.

Cloud Setup Architecture:

  Pre-Requirements for Azure :
 
    •	Azure Subscription.
    •	Storage accounts for VM's & Data store.
    •	Virtual Network with four subnets.
    •	Network Security Groups, one for each subnet.
    •	External Load Balancer to load balance Web Traffic(HTTP & HTTPS) to web servers.
    •	Internal Load Balancer to load balance traffic for app VM's.
    •	2 Public IP’s, one for external Load balancer and other for Jump VM.
    •	3 Virtual Machine Availability sets for Web Tier, Application Tier and Database tier.
    •	One Jump VM to facilitate ssh access to all other tier VMs.
    •	Multiple Red Hat Enterprise Linux VMs for each tier as per parameter value specified during deployment.
      
 ![image](https://user-images.githubusercontent.com/106581159/171143626-bebb7b57-b476-4a5f-b9e3-9c1589e41da3.png)

  Pricing :
  
    Pay as You Go model helps to manage the pricing for Azure resoures and doesn't require the user to license.
