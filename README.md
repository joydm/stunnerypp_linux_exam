# stunnerypp_linux_exam
B. Linux Exam

1. How to check the current load of server

  On Linux, you can check the server load using the following command:

    a. uptime
    This command can show how many days, hours and minutes the server has been up; the number of users logged in and the server load average.
    
    b. top
    This command displays real time information regarding the server’s resource usage.  It can show which process is receiving the biggest demands on its resources.

    c. free
    This command displays information regarding the server’s memory usage. The first few lines provide a summary of the memory usage on your system. 

  On Windows, you can check the server load using the following applications:

    a. Task Manager provides quick access to Processes, Performance, Users, Details, and Services.
    b. Resource Monitor provides data on CPU, Memory, Disk, and Network options and graphs.


2. What is nginx -t and apachectl -S ?

  a. nginx -t
  This command is used to test the nginx server’s configuration file before doing a restart or a reload on the server. The errors or warnings displayed can help prevent your site to go down.

  b. apachectl -S
  This command is used to list all enabled virtual hosts on the web server. This can help troubleshoot blank pages or domain issues. 

3. Check current swap usage

  a. vmstat
  If swap space is configured, this command is used to show how much data is moved to free up physical memory or swapping is occurring on your server. 

4. Create a vhost config that will handle http and https traffic under apache
        
        See vhost_apache.conf

        To test, access your sites for both http and https
        http://landosonglist.com
        https://landosonglist.com


5. Create a vhost config that will handle http and https traffic under apache
        
        See vhost_nginx.conf

        You can add a redirection from http to https and access and/or
	      To test, modify your local hosts file to include the ip address and the domain of your project
	      http://landosonglist.com




