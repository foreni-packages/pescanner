INSTALLATION:

1) First install forensics repository.

2) yum --enablerepo=forensics -y install python-pefile.noarch 

3) yum -y install python-magic

4) yum -y install yara.x86_64 

5) yum -y install yara-python

6) pip install ssdeep

7) rpm -Uvh http://download.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm &>/dev/null

8) yum install clamav clamd 

9) clone this repository : using git clone.

Note : Above steps are for centos. In case if any of the above dependencies doesn't work, search in google for specific repositories you need to install/enable.