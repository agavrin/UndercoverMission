

# Испытание агента UNDERCOVER

## ( СКРЫТО - НЕ ИСПОЛЬЗОВАТЬ - СОВЕРШЕННО СЕКРЕТНО)

![](assets/undercover.png)

Это **приложение NodeJS** поможет новому агенту Undercover познакомиться с нашими системами.

Вам будет предоставлена вся необходимая информация, чтобы подключиться к секретной системе UnderCover Network System.

Разверните это приложение в RedHat Openshift cluster, работающем в IBM Cloud и откройте приложение в браузере.

### Тебе потребуется:

- Браузер
- Доступ к RedHat OpenShift Cluster в облаке IBM
- Эта ссылка на GitHub

## ИНСТРУКЦИЯ

- #### Залогиньтесь в IBM Cloud (https://cloud.ibm.com)
- #### Найдите ваш кластер Openshift

  - Кто-то сказал, что известный хакер "Alexander Gavrin" открыл свой аккаунт для всех.
    - Ты смо You might find his account "under" your name  (click on your name in the console or [here](https://cloud.ibm.com/?bss_account=6c8f4926207a904b377aee72d8cd861e))
    - If you see a cluster, open it (or click [here](https://cloud.ibm.com/kubernetes/clusters/c19h9sjf0ecruimc5ngg/overview?region=eu-de&resourceGroup=799d42eab36346bdac7c23cf2c874c17&bss_account=6c8f4926207a904b377aee72d8cd861e))

![image-20200917151418908](assets/image-20200917151418908.png)

- #### Open the Openshift Console

  - You need to **allow pop-up** windows as a new tab will open
  - First access should take a few seconds - You might need to close the page and click again on the "Openshift web console" button

- #### **As a developer, <u>SELECT YOUR TEAM PROJECT</u> not "default" project**

  ![image-20200917151811301](assets/image-20200917151811301.png)

- #### Create new NodeJS web application **FROM GIT** from this Git in your team's project

  - Copy the URL from this Git repository

  - Check this a NodeJS application

  - **<u>Change</u>** the name of your application

      ![image-20200917153510852](assets/image-20200917153510852.png)

  - And hit the **Create** Button ![image-20200917153441240](assets/image-20200917153441240.png)

    - It takes a few minutes to build and deploy the application
    - Look at the logs if you want to discover what is appening under the cover

#### Once the application is deployed (green checkmark, blue circle), click on Open URL

![image-20200917153603053](assets/image-20200917153603053.png)

#### Generate you One-time-password to unlock the undercover server



**<u>WELCOME ON BOARD NEW AGENT!!!</u>**

![](assets/undercover.jpg)
