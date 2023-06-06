# 2bPrecise task Gateway application


## Running the application
Open terminal in the project folder.<br />
Run command: ./mvnw spring-boot:run<br />
<br />
The server will start on port 8081.<br />
Port configuration can be found in the application.yml file.<br />
<br />
<br />
This project is meant to rout the calls of the FE and BE so we wont have cross domains exceptions.<br />
Our common ground will be localhost:8081 and the calls will be directed to the relevant server.<br />
The routing configurations can be found in the application.yml.<br />