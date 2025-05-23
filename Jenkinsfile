pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Build step is the place that the source code is compiled and assembled into deployable format "
                echo "Helps to identify issues and resolve early"
                echo "Build Automation Tools - Maven"
            }
        }
        stage('Unit and Integration Tests'){
            steps{
                echo "In this stage, individual units or components of a software application are tested independently to ensure they are worked as expected."
                echo "In the integration test, we ensure that all the components are worked together as expected and verify that connection between each components in the software application. "
                echo "Unit Testing Tools - Selenium"
            }
        }
        stage('Code Analysis'){
            steps{
                echo "During this stage, integrate a code analysis tool to analyse the code quality and check the code standards"
                echo "Code Analysis tool - SonarQube"
            }
        }
        stage('Security Scan'){
            steps{
                echo "Identify any vulnerabilities and security risks in components"
                echo "Security Scan tool - Synk"
            }
        }
        stage('Deploy to Staging'){
            steps{
                echo "Test the software application before going to production environmnet."
                echo "Automation Tool - AWS EC2 instances"
            }
        }
        stage('Integration Tests on Staging'){
            steps{
                echo "After deployment, identify any performance issues and verify that application is working as expected."
                echo "Automation Tool - Selenium"
            }
        }
        stage('Deploy to Production'){
            steps{
                echo "Ensure that the software application is stable and error free for the real-world use."
                echo "Automation tool - AWS EC2 instance"
            }
        }
    }
}
