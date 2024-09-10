# DevOps-Project-Netflix-Clone-Aws
![image](https://github.com/user-attachments/assets/e9435a2c-c012-402b-a344-127f2f998e51)

For Monitoring Jenkins using Prometheus and Grafana the plugin prometheus metrics has been installed as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/37875226-a8a6-4f68-837b-9fbb551d69b5)
After installation of prometheus metrics plugin restart the Jenkins as shown in the screen attached below.
![image](https://github.com/user-attachments/assets/dc18f027-62d3-44d1-8090-0a7641b1ad30)
![image](https://github.com/user-attachments/assets/414706bd-d0f8-4863-ac1e-2e22084bd620)
Now prometheus metrics plugin will be shown in the list of installed plugins as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/c766ca74-1ec8-4d44-946f-c3b7b1189ac2)

Configuration file for prometheus **/etc/prometheus/prometheus.yml** is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/e9450c70-23c4-4e13-92a0-edbcbf6480c6)

Targets of Prometheus is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/0db8e559-4511-467d-b576-0d56a5b58cad)
![image](https://github.com/user-attachments/assets/a5429685-eb10-4504-b21e-a2e13501a2cd)

Prometheus is used as a Data Source for Grafana is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/1c69c01c-28ef-4154-8e63-ac50e27e6fd6)
![image](https://github.com/user-attachments/assets/ef5dbe42-5510-4077-8ec3-8ead0ae5e3ce)

Dashboard has been imported using the Code 1860(for Node Exporter) and 9964(for Jenkins and Jenkins Job) is as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/915708f9-e827-4791-a5bf-77063f25c761)
![image](https://github.com/user-attachments/assets/a81daede-1cb3-4480-873b-997ca4a8992e)

Install SonarQube Scanner plugin and do its configuration as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/5d1fe990-aa55-41ac-88d1-bfb799701ecd)
![image](https://github.com/user-attachments/assets/4487c5dc-90ae-4c84-921a-cc963518811f)

Do the Email configuration in Jenkins as shown below.
![image](https://github.com/user-attachments/assets/3d08a9e5-61ae-48a2-8bf4-ec29cde3ba10)
![image](https://github.com/user-attachments/assets/d901c684-009b-4385-86d1-cb990fc10e82)

After Running the Jenkins Job Successfully, the screenshot of SonarQube, ArgoCD is as shown below.
![image](https://github.com/user-attachments/assets/7b608a46-6b1b-4ebe-9e12-3761065acadd)
![image](https://github.com/user-attachments/assets/7ffcc45a-6f99-403c-ade4-4650814955c2)

The entry for Route53 is as shwon below.
![image](https://github.com/user-attachments/assets/c1e3cf6f-fba3-4365-9684-cd2078beac5b)

Finally you can access the Application as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/8b6640da-0f9a-42ff-8022-07e1fba99b6b)

After execution of Jenkins Job, email will be triggered to group email id for notification of Jenkins Job Completion Status.
![image](https://github.com/user-attachments/assets/867f4e72-744f-4edc-98e4-29796310e896)
![image](https://github.com/user-attachments/assets/b9d66e0b-066d-4965-928d-88b199864d6a)

TMDB API Key can used as shown below while building the Docker Image.
![image](https://github.com/user-attachments/assets/9e035c58-a3f8-4b3c-a647-ee60d6f5552b)



<br><br/>
<br><br/>
<br><br/>
<br><br/>
<br><br/>
```
source Code:- https://github.com/kamalmohan217/DevSecOps-Project.git

Helm Chart:-   https://github.com/kamalmohan217/helm-repo-for-netflix-clone.git
```
<br><br/>
<br><br/>
<br><br/>
```
Reference:-  https://muditmathur121.medium.com/devsecops-netflix-clone-ci-cd-with-monitoring-email-990fbd115102
```
