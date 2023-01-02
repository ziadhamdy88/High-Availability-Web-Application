# High-Availability-Web-Application

Deployed a high-availability web application through the use of AWS services like Cloudformation.
Developed a network infrastructure that contained an Internet gateway, 2 public subnets, and 2 private subnets.
Deployed 4 servers separated into 2 availability zones on these private subnets.
Implemented 2 NAT gateways in the public subnets to redirect access of the private web servers to the internet gateway.
Deployed an S3 bucket to allow the servers to download the application and keep up with the updates.
Deployed an Application LoadBalancer to distribute the load on the 4 servers evenly.
