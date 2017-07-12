# SSH Warning Banner Example
This a basic warning banner for SSH connections

Edit issue.net and save the file

`sudo vim /etc/issue.net`

Open sshd_config and set the path for the banner

`sudo vim /etc/ssh/sshd_config`

Uncomment if needed

`Banner /etc/issue.net`

Restart SSH

`sudo /etc/init.d/sshd restart`
