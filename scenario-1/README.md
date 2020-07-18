### Scenario 
Terrafrom script to perform below :
1. Create VPC
2. Create Internet Gateway
3. Create Custom Route table
4. Create a Subnet
5. Associate Subnet with Route table
6. Create a Security Group to allow port 22,80,443
7. Create a network interface with an IP in the subnet that was created in Step 4
8. Assign an elastic IP to the network interface created in Step 7
9. Create Ubuntu Server and install/enable apache2
