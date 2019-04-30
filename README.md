## springboot-webpack4-vue2-gradle-docker-boilerplate
适合做一些小项目

#### 前端脚手架

相见

/src/main/resources/web/package.json

运行`npm run dev`调试前端代码，webpack自动开启3000端口，并代理localhost的8080端口进行调试。

运行`npm run build`编译前端代码，编译好的代码会放到/src/main/resources/static下



#### gradle

gradle自动化构建springboot项目。

修改settings.gradle文件中的rootProject.name（项目名称）。

修改build.gradle文件中的ext.dockerRepo(docker私服地址)。

运行`./gradlew build`编译java代码

运行`./gradlew docker`编译并生成docker镜像，push到私有仓库中。	

