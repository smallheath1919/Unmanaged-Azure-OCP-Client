# Unmanaged Azure OCP Client

The Unmanaged Azure OCP Client is a simple Bash based utility that currently minimizes the trouble of manually starting and stopping node VMs in a specific sequence. Instead it uses commands with options similar to Az CLI, like resource group and name of the cluster.

We plan on introducing more features going forward.

## **Pre-requisites:**<br><br>
Installation of an Openshift Cluster on Azure. [How-to guide](https://cloud.redhat.com/openshift/install/azure/installer-provisioned)
<br><br>
## **Getting Started**

Installation instructions:

```
curl -L https://github.com/smallheath1919/test/blob/main/client-ocp.tar.gz | tar -xzf
sudo mv ocp* /usr/local/bin

```
<br><br>
## **Screenshots**

![image](https://user-images.githubusercontent.com/41380074/118137744-2dc9ff80-b423-11eb-9cc8-1cdb0a3fe895.png)

![image](https://user-images.githubusercontent.com/41380074/118139301-d75dc080-b424-11eb-93bc-82a672fedf4b.png)

![image](https://user-images.githubusercontent.com/41380074/118139495-096f2280-b425-11eb-9d26-f00f3b35ba7a.png)
