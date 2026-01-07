# app-frontend-deployment-files-for-dev-environment
Create Kubernetes deployment files for the frontend application in the development environment.


        
      Deployment file should include Kubernetes deployment, service, and configmap.

        
      Service should be nodePort

        
      Configmap Env. Variables:

REACT_APP_BASE_URL: http://${NODE_IP}:Port  #IP number or DNS name - Base URL for making API calls and accessing backend services


Acceptance Criteria

Kubernetes deployment, service, and configmap files are created.
