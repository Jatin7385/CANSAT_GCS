# SAMPLE-CANSAT-GCS
Hey!!
So this is a Sample CANSAT Ground Control System that I made using Javafx and SceneBuilder
To read more about Cansat : http://cansatcompetition.com/
This software has the job of collecting data from the Flight Software, and plotting/storing it in real time. For the real time plotting and storing functionality, I have used ScheduledExecutorService.
I have also created multiple tabs to view the data in. There is a tab to view our team's 3D cansat models. It has an altimeter and horizon to view the altitude, pitch and roll on the device.
The software also displays the exact position of the carrier on a map.

### Commercial off the shelf (COTS) software packages used
* Development Environment : IntelliJ IDEA, Scene Builder
* Programming Suite : Javafx,Fxml,html,css,javascript
### Real-time plotting software design
* This GCS software contains tabs to view each graph separately as well as all together.
* Real time plotting is being conducted using ScheduledExecutorService
* In a scenario where the values of certain data parameters goes out of the expected range, the plot lines turn red, otherwise it remains green.


## Commands and Tools
### Commands
* Calibrate : To calibrate sensors	
* Set Time : To set UTC time in carrier.
* Telemetry : To begin telemetry
### Tools
* LineCharts(Javafx module) for Graphs
* mapjfx for displaying maps in real time
* ScheduledExecutorService for real time plotting.
* eu.hansolo.airseries for Altimeter and Horizon
* com.digi.xbee.api for xbee communications
* com.interactivemesh.jfx for 3D Models

### CSV file creation 
* The two CSV files(Carrier.csv & Science_payload.csv) are created after telemetry begins.A function has been created in Javafx which writes into the CSV files in real time.



## Software Designs
![Picture1](https://user-images.githubusercontent.com/73430464/121590907-85757e00-ca56-11eb-939f-d9242aa5cf1e.png)
![Picture7](https://user-images.githubusercontent.com/73430464/121591108-ba81d080-ca56-11eb-8b1c-6f1c4ae68144.png)
![Picture8](https://user-images.githubusercontent.com/73430464/121591111-bbb2fd80-ca56-11eb-8474-53206dee3755.png)
![Picture9](https://user-images.githubusercontent.com/73430464/121591113-bd7cc100-ca56-11eb-8938-e35fae785a99.png)
![Picture10](https://user-images.githubusercontent.com/73430464/121591117-be155780-ca56-11eb-9152-84cc342500c3.png)
![Picture13](https://user-images.githubusercontent.com/73430464/121591147-c53c6580-ca56-11eb-83f7-9b12e18214dd.png)
![Picture14](https://user-images.githubusercontent.com/73430464/121591152-c66d9280-ca56-11eb-9748-d094f7f99cfb.png)
![Picture15](https://user-images.githubusercontent.com/73430464/121591179-cd94a080-ca56-11eb-8739-df3dd97b2a26.png)
![Picture16](https://user-images.githubusercontent.com/73430464/121591187-d08f9100-ca56-11eb-8352-1aa7056f1c46.png)
