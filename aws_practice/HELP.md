# Getting Started

### Reference Documentation

For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.0.12/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.0.12/gradle-plugin/reference/html/#build-image)

### Additional Links

These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

putty -> ppk

ec2-user

jdk 설치
* yum list java*
* sudo yum install java-17-amazon-corretto.x86_64

git 설치
* sudo yum install git

깃허브에 SSH 등록
* cd ~/.ssh
* ssh-keygen -t rsa -C <git email>
* cat id_rsa.pub

깃 클론
* git clone <github clone -> SSH>

프로젝트 빌드후 실행
* ./gradlew build (권한 없으면 -> chmod +x gradlew)
* cd build/libs
* java -jer <.jar 파일명>

