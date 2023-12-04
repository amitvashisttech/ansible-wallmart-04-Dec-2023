
## Environment Setup 

### Step1 : Open the GitBash / console / cmder / powershell 

### Step : Make a Clone 
```
git clone https://github.com/amitvashisttech/vagrant-setup.git
```

### Step2 : cd vagrant-setup/devops

### Step3 : Now check the Vagrant Status 
```
vagrant.exe status 
```

### Step4 : Bring up the master virtalbox instances 
```
vagrant.exe up master
```

### Step5 : Let's Login to master node.
```
vagrant.exe ssh master
```

### Step6 : Become a super user
```
sudo su - 
```

### Step7 : Clone our Ansible Repo. 
```

```


 
## Extra Vagrant Command  :
### Bring up a specific virtalbox instances 
```
vagrant.exe status 
vagrant.exe up master 
```
### Bring down a specific virtalbox instances 
```
vagrant.exe status 
vagrant.exe halt master 
```

### Destroy a specific virtalbox instances 
```
vagrant.exe status 
vagrant.exe destroy master 
```
