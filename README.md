https://www.cisco.com/c/en/us/support/docs/cloud-systems-management/iox/211534-Configure-a-Small-Alpine-Linux-Docker-Im.html

Requires to install iox_client and docker on your host machine

take iox_client_pythonweb/

cd iox_client_pythonweb/

$docker run -t ioxpythonweb:1.0 .
$docker image
$docker run -ti ioxpythonweb:1.0
 ..image runing...
 /# python /webserver.py 900 &
 
 /# netstat -tlpn
 /#exit
