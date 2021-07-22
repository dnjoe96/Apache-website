##steps  

- setup a vm of Azure cloud

- installed git
	`yum install git`
	
- Downloaded a html template from *[free-css.com](free-css.com)*

- copied the website files to the linux server with winscp

- created a github repository, added and commited the file, and pushed to origin

- installed Apache web server
	`sudo dnf install httpd`
	`sudo systemctl enable httpd`
	`sudo systemctl start httpd`
	`sudo systemctl status httpd`

- if you need your Apache web server to be accessed from remote locations open HTTP firewall port 80:
	`sudo firewall-cmd --zone=public --permanent --add-service=http`
	`sudo firewall-cmd --reload`
	
- copied the website files into */var/www/html/*  directory






