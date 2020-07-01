1. To connect to aws account and run aws command need to install python boto using pip
   Below is the command to install boto

   if you have pip package then use below command
   #pip install boto
   if you have pip3 install then use below command
   #pip3 install boto

2. Once you install boto then you need to provide aws credentials in .boto file which will 
   presnt in root dir. i.e. /root/.boto

3. Create IAM user in your aws account and assign ec2fullaccess policy to that user and give
   programatic access to the user.

4. copy access_key_id and secret_access_key in the .boto file mentioned in step 2
   below is the format fo .boto file.

[Credentials]
aws_access_key_id = 
aws_secret_access_key =
