Title : Automation_Project
In this project we will be following the below mentioned steps
1. Create an IAM Role
2. Create Security Group
3. Create and EC2 Instance in the AWS console
4. Create a S3-bucket
5. Do the SSH on the EC2 Instance
6. Write a bash script with below functionality
	a. Run update command to get the update of the packages
	b. Run a command to check if apache2 package is installed or not.
	c. If not install, then run a command to install apache2 package and check the status
	d. Create a tar file of all the logs in /var/log/apache2 path
	e. Move the tar file to the /tmp folder
	f. Upload the tar file in tmp folder to S3-bucket
