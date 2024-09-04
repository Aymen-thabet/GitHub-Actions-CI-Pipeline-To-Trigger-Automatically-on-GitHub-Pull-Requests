The main idea is to use GitHub Action to trigger a checkout , build , test code on a ubuntu runner and check if the pull request has no conflicts : 

![Capture d'écran 2024-09-04 194900](https://github.com/user-attachments/assets/34c27ca7-3df2-4ddb-bb9f-9708b7fe50b4)

The app  :  https://github.com/Aymen-thabet/simple-java-app

First thing to do is to create the YAML file for the CI : we will use checkout so that the runner can clone the repo and work on it and the maven to build and test 

![Capture d'écran 2024-09-04 195327](https://github.com/user-attachments/assets/d7a1216b-9208-47ed-9a98-5497b3fba991)

After pushing the Ci yaml file , we need to checkout to another branch , modify README.md then commit and push it 

![Capture d'écran 2024-09-04 195448](https://github.com/user-attachments/assets/9d7d5472-bac2-4552-9c42-cc05924c95b7)

![Capture d'écran 2024-09-04 195702](https://github.com/user-attachments/assets/11a4898b-1cff-411e-a18b-b6413c9177e5)

![Capture d'écran 2024-09-04 195910](https://github.com/user-attachments/assets/c70e3ae7-b406-4f03-8837-509d56257b89)

Once the push is finished , we can make a pull request now : 

![Capture d'écran 2024-09-04 195928](https://github.com/user-attachments/assets/22407cd7-5050-4a9e-b181-eacadf9d0b44)

![Capture d'écran 2024-09-04 200537](https://github.com/user-attachments/assets/df065d11-4a1b-4a94-91ef-afd9747d68b5)

We create a pull request and the CI workflow is working :

![Capture d'écran 2024-09-04 200559](https://github.com/user-attachments/assets/c499d6d0-8f46-4c86-9ded-8741300e205d)

![Capture d'écran 2024-09-04 200635](https://github.com/user-attachments/assets/95a5dda3-d569-4096-a220-24c43d33c037)

all steps are finished succesufully ! 

![Capture d'écran 2024-09-04 200648](https://github.com/user-attachments/assets/2048eda1-5744-4ad4-9b9b-6dd1f109ba73)

and finally we are able to merge ! 

![Capture d'écran 2024-09-04 201029](https://github.com/user-attachments/assets/2e6cdff6-1fe2-47c6-8123-128d9740c53a)


