# Readme need for explain how to work with API

### Implement API to project

1. You need to add dependency that you need API or Client for your Spring Project:
    - Add this repository to you *pom.xml*
   ```
   <repositories>
        <repository>
            <id>github</id>
            <url>https://maven.pkg.github.com/vlad-vinskevitch/app-afesox</url>
        </repository>
    </repositories>
    ```
   - Set API dependency to *pom.xml*. Pay attention on that ```<version>0.0.4</version>``` version will be another, please use actual version API. Actual version marks  in *app-afesox-athssox-api-first-__stable__*
   ```
   <dependency>
      <groupId>com.afesox</groupId>
      <artifactId>app-afesox-athssox-api-first-stable</artifactId>
      <version>0.0.4</version>
   </dependency>
   ```
   - Set Client dependency to *pom.xml*. Pay attention on that  ```<version>0.0.4</version>``` version will be another, please use actual version API. Actual version marks  in *app-afesox-athssox-client-__stable__*
   ```
      <dependency>
         <groupId>com.afesox</groupId>
         <artifactId>app-afesox-athssox-client-stable</artifactId>
         <version>0.0.4</version>
      </dependency>
   ```
2. Update your maven project dependency and reinstall project ```mvn clean install```

### Generate unstable version API/Client and implement

1. Create pull request, and when you set name *pull request name* need to follow the **rule**:
   - Pull request name must be like this ```[SITIONIX-1]``` + ```descripton to pull request```. In first block explain that Pull request must starts and ends **square brackets**, inside brackets you need to set **branch name** with **uppercase**

2. When you create *Pull request* you need to wait all validation and write comments by **rule**:
   - Example command ```/generate --name "API Authentication SOX"```. ```/generate --name``` is keywords and ```API Authentication SOX``` this name you can get from [this](https://github.com/vlad-vinskevitch/app-afesox/blob/develop/apis/metadata.yml) file 














