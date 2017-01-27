# Ansible Role: Zookeeper #

The Ansible role installs Zookeeper.

### Install with ansible-galaxy ###

Content of the *requirements.yml* file for zookeeper role:

	- src: git+https://bitbucket.org/ueisele/iac-ansible-roles-zookeeper
	  version: 1.0.0
	  
Command to install the zookeeper role form requirements file:	  
	  
	  ansible-galaxy install -r requirements.yml
	  
For further information see: https://opencredo.com/reusing-ansible-roles-with-private-git-repos-and-dependencies/
