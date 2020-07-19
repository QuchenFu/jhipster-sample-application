 # jhipsterSampleApplication

This application was generated using JHipster 6.10.1, you can find documentation and help at [https://www.jhipster.tech/documentation-archive/v6.10.1](https://www.jhipster.tech/documentation-archive/v6.10.1).

## Development

This assignment requires a lot of development environment set up work. You should start early (e.g., before office hours). Almost all future assignments will build off of this set up work. Future assignments will assume and require that you completed this assignment successfully.
Complete all of the steps listed below and then submit the items listed in the last step.

1. Install java14
* [Mac](https://mkyong.com/java/how-to-install-java-on-mac-osx/)
* [Linux](https://www.linuxuprising.com/2020/03/how-to-install-oracle-java-14-jdk14-on.html)

2. Download and install [Intellij](https://www.jetbrains.com/idea/) and Google Chrome

3. Open intellij and install plugin: Gradle
<img width="600" alt="Screen Shot 2020-07-15 at 4 52 31 PM" src="https://user-images.githubusercontent.com/68395173/87865652-a49a8700-c93d-11ea-840b-0015bc0e34f6.png">
<img width="600" alt="Screen Shot 2020-07-15 at 4 52 52 PM" src="https://user-images.githubusercontent.com/31392274/87865805-09a2ac80-c93f-11ea-8271-6f99e0d23937.png">

4. In intelliJ configure SDK to use Java14
<img width="600" alt="Screen Shot 2020-07-15 at 4 51 32 PM" src="https://user-images.githubusercontent.com/31392274/87865878-fc39f200-c93f-11ea-9f17-e3386c090a36.png">
<img width="600" alt="Screen Shot 2020-07-15 at 4 52 02 PM" src="https://user-images.githubusercontent.com/31392274/87865894-268baf80-c940-11ea-88de-a7d991dc160a.png">

5. Accept this [homework invitation](https://classroom.github.com/a/9wgJ8ily) and git clone the project to your computer

6. Import the project as a Gradle project into Intellij
<img width="600" alt="Screen Shot 2020-07-15 at 4 57 23 PM" src="https://user-images.githubusercontent.com/31392274/87865918-84b89280-c940-11ea-97b1-ed638e3a2afb.png">
<img width="600" alt="Screen Shot" src="https://user-images.githubusercontent.com/31392274/87865931-a87bd880-c940-11ea-8927-101dcffe5f47.png">

7. Right click on the file with a green arrow to run the application and make sure that you can access http://localhost:8080 via browser
<img width="600" alt="Screen Shot 2020-07-15 at 4 59 17 PM" src="https://user-images.githubusercontent.com/31392274/87865999-83d43080-c941-11ea-8abe-be4d689e1f08.png">

8. You can also make a request by “curl” command in the terminal. Click the terminal button on the bottom left and type “curl http://localhost:8080”, press Enter
<img width="600" alt="Screen Shot 2020-07-15 at 5 16 28 PM" src="https://user-images.githubusercontent.com/31392274/87866017-bc740a00-c941-11ea-9288-c964b9aa607a.png">

9. Take a close look at the html content returned, yes, it is exactly the same as what you see in the browser. Try to make apost request and see what got returned by type “curl -X POST http://localhost:8080” in the terminal. You can also try to make different request to the endpoint http://localhost:8080 by following the [tutorial](https://curl.haxx.se/docs/manpage.html)

10. Stop the application by click the red stop button on the bottom left
<img width="600" alt="Screen Shot 2020-07-15 at 4 59 29 PM" src="https://user-images.githubusercontent.com/31392274/87866533-956d0680-c948-11ea-89e2-a2251a3d2ec3.png">

11. Submit the following files
* A screenshot of the browser after it has loaded your application on http://localhost:8080
* A screenshot of the project imported into Intellij
