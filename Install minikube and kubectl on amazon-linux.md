# Install Minikube on Amazon Linux
	* wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
	* chmod +x minikube-linux-amd64
	* sudo mv minikube-linux-amd64 /usr/local/bin/minikube
	* minikube version

# Instāll kubectl
	* wget  https://dl.k8s.io/release/v1.23.0/bin/linux/amd64/kubectl
	* sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
	* kubectl version --client
	* sudo yum install conntrack
