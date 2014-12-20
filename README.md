## Usage

1. Install at least the following software
   - [Vagrant](https://www.vagrantup.com/downloads)
   - Oracle virtualbox
   - Ansible
   - git

1. Clone this repository

1. Set the environment variable `VAGRANT_GIT_REPO`. Ansible will try to check
   out the specified url
   
   To have vagrant automatically deploy a private github repo, use the HTTPS
   url with oath token in the format https://<token>@github.com/owner/repo.git
   
   See
   https://github.com/blog/1270-easier-builds-and-deployments-using-git-over-https-and-oauth

1. `vagrant up` 

## TODO 

- use pip to install `/vagrant/src/requirements.txt` 
