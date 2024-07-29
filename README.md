Hello there!
**this is a simple Project to Create Single Deployment Using Helm and K8s**

**Task 1: Containerize and Push Your Application**
Build and push the image

Your task is to:

    Create a Docker image
    Push this image to Docker Hub

**Task 2: Set Up the Environment**
Your task is to:

    Change the directory to /usercode
    Verify that the Helm installation script is available.
    Set up Helm
    Verify that Helm is installed correctly.

**Task 3: Set Up the Cluster**
Your task is to:

    Create a kind cluster.
    Verify that the cluster has been created.

**Task 4: Set Up the Chart**
In Helm, a package is known as a chart. It is a set of Helm-specific files that install an application on a Kubernetes cluster. A Helm chart helps us deploy applications ranging from simplest to the most complex.

Your task is to create a Helm chart template.

**Task 5: Configure the Chart**
Your task is to:

    Configure the chart to use your repository name.
    Change the image tag to the one you recently created.

**Task 6: Configure the Service**
Your task is to:

    Change the Service type to NodePort.
    Configure the chart to use the 31111 port.

**Task 7: Verify the Values**
Before moving, check if the application is configured correctly, meaning that it is using the correct Service, running on the desired port, and is the correct image name.

**Task 8: Configure the Deployment**
Every application has unique functionality and may run on the same or different ports depending on the application type. In a deployment.yaml file, a containerPort is the port on which your application is accessible inside the container.

**Task 9: Deploy the Chart**
Your task is to:

    Install the Helm chart.
    Verify the Pod status.

**Task 10: Access the Application**
Your task is to:

    Check the status of your Service.
    Access your internal Kubernetes application over the internet. To do that, map your Service port to 31111.

**and here the result!**

![image](https://github.com/user-attachments/assets/cc3e5997-5e76-49e8-b5a7-f7778c27cf05)
