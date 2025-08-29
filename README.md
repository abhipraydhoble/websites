# staticwebsites

```sh
#!/bin/bash
sudo -i
yum install httpd -y
yum install git -y
systemctl start httpd
systemctl enable httpd
cd /root/
git clone https://github.com/abhipraydhoble/staticwebsites.git
```
