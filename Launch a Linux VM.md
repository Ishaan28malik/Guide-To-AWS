* Beginning with Amazon Elastic Compute Cloud (EC2)

First configure the EC2 instances , if you are a windows user you will need Git Bash and for Mac/Linux users no need of any external ttols


* Launch EC2 

Set the Account and then you will be taken to vocareum.com where all your credentials and account credits are shown 
Now click to launch AWS console .
In the services you need to select EC2 .
Once selected launch the instances and also download the key with .pem ext and save it in the .ssh dirct.

if you don't have .ssh in your system then make a dirct in your users using mkdir .ssh

* Config the Instances

Once done with setting up the instance then follow the below mentioned commands

Also it's upto you to take free tier or paid .

* ssh -i {full path of your .pem file} ec2-user@{instance IP address}
## where Ip address is in the instace as public IPV4 ##

* The authenticity of host 'ec2-198-51-100-1.compute-1.amazonaws.com (10.254.142.33)' can't be established. RSA key fingerprint is 1f:51:ae:28:df:63:e9:d8:cf:38:5d:87:2d:7b:b8:ca:9f:f5:b1:6f. Are you sure you want to continue connecting (yes/no)?

yes to proceed

* Warning: Permanently added 'ec2-198-51-100-1.compute-1.amazonaws.com' (RSA) to the list of known hosts.
