helm install --name jenkins-demo stable/jenkins --set Agent.Enabled=false --set Master.ServiceType=NodePort
