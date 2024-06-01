0x1B. Web stack debugging #4
Requirements
General
All your files will be interpreted on Ubuntu 14.04 LTS
All your files should end with a new line
A README.md file at the root of the folder of the project is mandatory
Your Puppet manifests must pass puppet-lint version 2.1.1 without any errors
Your Puppet manifests must run without error
Your Puppet manifests first line must be a comment explaining what the Puppet manifest is about
Your Puppet manifests files must end with the extension .pp
Files will be checked with Puppet v3.4
Install puppet-lint
$ apt-get install -y ruby
$ gem install puppet-lint -v 2.1.1
Tasks
0. Sky is the limit, let's bring that limit higher
In this web stack debugging task, we were testing how well our web server setup featuring Nginx is doing under pressure and it turns out it’s not doing well: we were getting a huge amount of failed requests.
1. User limit
Change the OS configuration so that it is possible to login with the holberton user and open a file without any error message.
