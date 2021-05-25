pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                                   sh '''#!/bin/bash
                                    sudo yum update
                                    sudo yum install -y httpd
                                    sudo systemctl start httpd
                                    sudo systemctl enable httpd
                                    echo "<h1>This is your newly created webserver using jenkins</h1>" > /var/www/html/index.html'''
                                   }
                 }
}
}
