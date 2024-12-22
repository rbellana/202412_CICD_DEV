# 202412_CICD_DEV
202412_CICD_DEV

# This is for testing

# git add .
# git commit -m "This is for pushing the changes"
# git push 

# Download and Install Kubectl 
curl -Lo kubectl https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl