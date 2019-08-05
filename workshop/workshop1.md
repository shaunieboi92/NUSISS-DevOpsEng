# Jenkins Installation

## Pre-requisites for Cloud installation
* AWS account

### Step by step installation
1. Navigate to the AWS services link
2. Select EC2
3. Launch a new instance, search 'bitnami jenkins' on the marketplace 
4. Choose Ubuntu 18.04 free tier
5. Generate a new key for the ssh login
6. Logon into the ssh session, change directory to /home/bitnami
7. Look for the username and password under the bitnami_credential file.
8. Retrieve ip4 public IP address or the DNS from the AWS jenkins instance console panel
9. Launch the web browser then access the jenkins web admin app.

## Pre-requisites for local workstatio installation
* Java JDK 9 or higher

### Step by step installation
1. Navigate the Jenkins official website. Download the WAR file from the LTS link. By default, the latest release and the Long-Term support release will be available for download. The past releases are also available for download. Click the Long-Term Support Release tab in the download section. 

<img style="width:650px;height:400px; float: right;" src="./screens/jenkins.png">

<br>

<img style="width:650px;height:400px; float: right;" src="./screens/jenkins2.png">

2. Open the terminal/command prompt. From the command prompt browse to the directory where the jenkins.war is saved. Run the following command

```
$ java -jar jenkins.war
```
