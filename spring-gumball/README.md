# spring-gumball

# Part 1 Screenshots
Used github actions/workflows and provided code to achieve result
![image](https://user-images.githubusercontent.com/74092425/204443315-03e7d2e6-4331-4db1-9a4b-b386f03c6f11.png)
![image](https://user-images.githubusercontent.com/74092425/204443339-1c682ae4-2662-4138-8572-9e4fcf72276a.png)
![image](https://user-images.githubusercontent.com/74092425/204443351-9a2e96f1-800e-487a-a49e-77c35a55736a.png)
![image](https://user-images.githubusercontent.com/74092425/204443389-1359299b-f208-4caa-a47b-27ba8c3f9c13.png)

# Part 2 Screenshots
Created cluster - Created standard cluster on GKE with medium sized nodes
![image](https://user-images.githubusercontent.com/74092425/204449812-4759729d-373c-46dd-b15d-4a242864fd1e.png)

Service account - Added service account to GCP with key
![image](https://user-images.githubusercontent.com/74092425/204450289-f00128e8-4822-4f21-b219-3861eacb856d.png)

Secrets - Added secret using GCP service account key, and another secret that has project id, according to instructions of lab
![image](https://user-images.githubusercontent.com/74092425/204451624-1737f7ab-772e-41a9-b20e-2b2da4a7ff8b.png)

Build and Deploy to GKE - Automated build and deployment to GKE results after creating new release
![image](https://user-images.githubusercontent.com/74092425/204453389-08f79c6e-9149-4721-8258-71cbcf5334ec.png)
![image](https://user-images.githubusercontent.com/74092425/204453466-4db9e407-cfb9-4de1-9346-3fb0377e07e1.png)
![image](https://user-images.githubusercontent.com/74092425/204453484-76f8a871-f1d1-47f7-9104-b6c271c3de05.png)

Gumball workload after automated build and deploy
![image](https://user-images.githubusercontent.com/74092425/204454020-ce568fa1-6cc4-4c83-a14d-b4d364683fc8.png)

Gumball service after automated build and deploy
![image](https://user-images.githubusercontent.com/74092425/204454136-6d36cfa0-4b9e-4601-9ba4-1fd5fec8ed5f.png)

Gumball ingress - Manually created ingress in GKE using the spring-gumball-service as backend, running in healthy state
![image](https://user-images.githubusercontent.com/74092425/204457517-8278ac75-03e1-4ef3-b65d-b5648ac2b193.png)

Working gumball application after ingress creation, by going to ingress port and viewing page
![image](https://user-images.githubusercontent.com/74092425/204456050-159824ee-38cc-420f-a4b4-62749e686f8b.png)

