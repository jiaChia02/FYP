# Smart Library System with JWO Concept 
### Purpose: to create a Smart library system with (Just Walk Out) JWO  by implementing AI technology included object detection and human action recognition 

## Configuration 
### Github (Optional)
#### Step 1: Right click on desktop and click on "Git Base Here"

#### Step 2: To check the existance of .ssh file: cd ~/.ssh/
1. If the file does not exist then, create file: mkdir ~/.ssh

#### Step 3: To configure Github account: 
1. git config --global user.name "youraccountname"
2. git config --global user.name "youraccount@example.com"

#### Step 4: To generate and add ssh key
1. ssh-keygen -t rsa -C "youracount@example.com"

3. cat ~/.ssh/id_rsa.pub 
a. copy all content start from ssh-rsa ....... until youraccount@example.com"
b. add them in the "SSH and GPG keys" --> "New SSH key" -->  authentication key

#### Step 5: To check the exist of new added SSH keys for authentication purpose
ssh git@github.com
enter [yes], if the authentication does not establish. 

Expected output:
Warning: Permanently added 'github.com' (????) to the list of known hosts.
Hi [youraccount]! You've successfully authenticated, but GitHub does not provide shell access.

## CUDA  
1. check cuda version which is compatible to your hardware and OS
2. Download CUDA and install in your device: https://developer.nvidia.com/cuda-toolkit-archive

For mine: NVIDIA CUDA version 11.6
CUDA Documentation --> C:\USers\chia\NVIDIA CUDA\CUDA1
CUDA Development -->  C:\USers\chia\NVIDIA CUDA\CUDA1
Samples -->  C:\USers\chia\NVIDIA CUDA\CUDA2

### CUDNN 
CUDA Documentation --> C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA
Sample --> C:\ProogramData\NVIDIA Corporating

### CMAKE
C:\Program Files\CMake\

## Virtual Environment 


