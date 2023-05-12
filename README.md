1. 
### Screenshots (in Markdown README.md) for CI Workflow (Part 1)
Preconfigured Gradle starter workflow
![images1](./images/part1/1.png)

Modify gradle.yaml
![images2](./images/part1/2.png)

Make change to the code and commit to main branch to trigger the action
![images2](./images/part1/3.png)
![images2](./images/part1/4.png)
![images2](./images/part1/5.png)
![images2](./images/part1/6.png)

2.
### This criterion is linked to a Learning OutcomeScreenshots (in Markdown README.md) for CD Workflow (Part 2)
Create a cluster
![images2](./images/part2/1.png)
![images2](./images/part2/2.png)
Enable the Kubernetes Engine and Container Registry APIs.
![images2](./images/part2/3.png)
![images2](./images/part2/3-1.png)
Find your GKE Project ID
![images2](./images/part2/4-1.png)
Create a Service Account for GitHub Access
![images2](./images/part2/5.png)
![images2](./images/part2/6-1.png)
Add the following Cloud IAM roles
![images2](./images/part2/7.png)
![images2](./images/part2/7-1.png)
Select Roles: Kubernetes Engine Developer & Storage Admin
![images2](./images/part2/8-1.png)
![images2](./images/part2/8-2.png)
Create a JSON service account keyLinks to an external site. for the service account.
![images2](./images/part2/8.png)
Select JSON Key
![images2](./images/part2/9.png)
Download JSON Key File
![images2](./images/part2/10.png)

Configure GitHub Secrets
![images2](./images/part2/11.png)
New Repository Secret: GKE_PROJECT
Set Value to: "Your GCP Project ID"
![images2](./images/part2/12.png)
New Repository Secret: GKE_SA_KEY
Set Value to: "The content of the service account JSON file"
![images2](./images/part2/13.png)
![images2](./images/part2/13-1.png)
Trigger and Deployment to GKE
![images2](./images/part2/14.png)
Trigger a CD Deployment by creating a new GitHub Release
![images2](./images/part2/15-1.png)
![images2](./images/part2/15-2.png)
![images2](./images/part2/15-3.png)
![images2](./images/part2/15-4.png)
![images2](./images/part2/15-5.png)
![images2](./images/part2/15-6.png)
GKE Workload
![images2](./images/part2/16.png)
GKE Services & Ingress
![images2](./images/part2/17.png)
GKE Create a Kubernetes Ingress
![images2](./images/part2/18.png)
![images2](./images/part2/19.png)
Result Gumball Machine on GKE
![images2](./images/part2/20.png)