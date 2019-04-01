wget http://repos.fedorapeople.org/repos/dchen/apache-maven/epel-apache-maven.repo -O /etc/yum.repos.d/epel-apache-maven.repo
sed -i s/\$releasever/6/g /etc/yum.repos.d/epel-apache-maven.repo

yum install maven -y

Deploying War to Tomcat using Jenkins

https://www.youtube.com/watch?v=5d9j4q_bWAE&list=PLj_XdGLdc5r_ftDjxlXYVQq0fXlr9W2o-&index=12
