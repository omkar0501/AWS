# what is Ec2 ?
   ec2 stands for elastic compute cloud that provide scalable virtual servers to run applications in the cloud.

# what is ami ?
   Ami stand for amazon machine image is a template that contain software configuration, including the operating system, application server, and applicatins required to launch an instance.

# what is instance types ?
   General purpose - balanced cpu, memory, and networking e.g. (t3, m5)

   compute optimized - high performence cpu for processing tasks  e.g. (c5, c6g)

   memory optimized - large ram for databases and  caching  e.g. (r5, x1e) 

   storage optimized - high speed storage for big data e.g. (i3, d2)

   Accelerated computing - GPUs and FPGAs for AI/ML e.g. (p3,G4)

# what is key pair ? 
   key pair are secure login information for your instance, To connect to the instance we use key pair that contain public key and private key.

# difference between public key and private key ? 
   public key - public key like a lock that is placed on ec2 instance 
                the public key is already on the instance 

   private key - private key is a key that is only you have 
                 you usse the private key to unlock the access it securely 

# difference between .pem and .ppk 
   .pem - for use with open SSH 

    .ppk - for use with PUTTY

# what is security Group ?
   A security Group acts as virtual firewall for your ec2 instance it is control inbound and outbound traffic based on defined rule 

   inbound rules - define what traffic allow in to the instance 

   outbound rules - what traffic can leave in the instance  

   

