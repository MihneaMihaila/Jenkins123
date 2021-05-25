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
                                    echo "<h1>JENKINS3</h1>" > /var/www/html/index.html'''
                                    
                                   }
                 }
}
}
