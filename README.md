# DevOps-ubuntu-terraform-terraform_installation.md
DevOps/ubuntu/terraform/terraform_installation
🔥 TERRAFORM  INSTALLATION ON UBUNTU 🔥

ec2-ubuntu 20.04-t2.micro-NEWKEYPAIR-SG-LAUNCH

<br />

## 🔹STEP-1
#### Update Ubuntu packages
```
$ sudo -i
$ apt-get update
```

<br />

## 🔹STEP-2
#### Change hostname
```
$ hostnamectl set-hostname terraform
$ bash
$ hostname
```

<br />

## 🔹STEP-3
#### Check Terraform version exist or not ?
```
$ terraform -v
```

<br />

## 🔹STEP-4
#### Install Terraform
```
$ wget https://releases.hashicorp.com/terraform/1.3.4/terraform_1.3.4_linux_amd64.zip
$ apt-get install unzip
$ unzip terraform_1.3.4_linux_amd64.zip
$ ls -l
$ cp terraform /usr/bin/
```

<br />

## 🔹STEP-5
#### Now check Terraform version
```
$ terraform -v
```

