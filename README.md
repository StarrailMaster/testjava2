**Intelligent E-commerce for ELEC 5620**

---
**Overview**

This project is an intelligent e-commerce platform based on the LLM model This platform simulates some basic functions of e-commerce platforms, enabling users to use login, registration, search, browse product information and other functions At the same time, an LLM model that interfaces with GPT 4 has been added, which can collect users' needs, preferences, and provide them with necessary information, recommendations, and other assistance in the form of intelligent customer service.
### Dependencies & Configuration

- **Frontend**:
  - `axios`: 1.7.7
  - `next`: 14.2.15
  - `react`: 18
  - `react-dom`: 18

- **Backend**:
  - `spring-boot-starter-data-redis-reactive`: 3.3.2
  - `spring-boot-starter-web`: 3.3.2
  - `spring-boot-starter-security`: 3.3.2
  - `firebase-admin`: 8.1.0
  - `okhttp`: 4.10.0
  - `java-dotenv`: 5.2.2
  - `json`: 20210307

- **Test Dependencies**:
  - `spring-boot-starter-test`: 3.3.2
  - `reactor-test`: 3.3.2

---

### Deployment Steps
1. **Upload project files to Github**

2. **Jenkins fetches project files through GitHub** 

3. **In the Jenkins project, use shell to package the project files with Docker and upload them to Aliyun Cloud Service**

4. **Jenkins pulls the image from Aliyun Cloud Service and deploys the project to the AWS cloud server**

---

### Advanced Technologies
1. **Application Frameworks**:
   - React
   - Next.js
2. **Cloud Services**:
   - Firebase
   - AWS
   - Aliyun
3. **Deployment Systems**:
   - Docker
   - Jenkins
