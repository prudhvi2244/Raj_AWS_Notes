# How to Install Minikube on Ubuntu
* To install Minikube on Ubuntu, follow the steps outlined below.
	* sudo apt-get update -y
	* sudo apt-get upgrade -y

* Also, make sure to install (or check whether you already have) the following required packages:
	* sudo apt-get install curl
	* sudo apt-get install apt-transport-https

* Install Docker
* Download the latest Minikube binary using the wget command
	* wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64

*  Copy the downloaded file and store it into the /usr/local/bin/minikube directory with
	* sudo cp minikube-linux-amd64 /usr/local/bin/minikube

* Next, give the file executive permission using the chmod command
	* sudo chmod 755 /usr/local/bin/minikube

* Finally, verify you have successfully installed Minikube by checking the version of the software
	* minikube version

* To deploy and manage clusters, you need to install kubectl, the official command line tool for Kubernetes
	* curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl

* Make the binary executable by typing
	* chmod +x ./kubectl

* Then, move the binary into your path with the command:
	* sudo mv ./kubectl /usr/local/bin/kubectl

* Verify the installation by checking the version of your kubectl instance
	* kubectl version -o json

* insṭall conntrack
	* sudo apt install conntrack

* Start Minikube
	* minikube start

* To see the kubectl configuration use the command:
	* kubectl config view

* To show the cluster information
	* kubectl cluster-info


