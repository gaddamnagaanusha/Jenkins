## Jenkins installation:

* sudo curl -o /etc/yum.repos.d/jenkins.repo \   https://pkg.jenkins.io/rpm/jenkins.repo
* sudo yum install fontconfig java-21-openjdk -y
* sudo yum install jenkins
* sudo systemctl daemon-reload

* sudo systemctl enable jenkins
* sudo systemctl start jenkins
* sudo systemctl status jenkins

* once installed open jenkins in browser using port 8080(default port number)
* sudo cat <link showing in the web>
* install plugins


