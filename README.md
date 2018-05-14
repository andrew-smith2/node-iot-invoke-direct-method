# Node-iot-invoke-direct-method
Simple node IOT device client
<br>
<ul>
<li>Sets up a calling application that registers with the Azure IoT hub and makees direct method call to a method called getTempFromDevice()</li>
<li>Takes returned payload from device method which contains a temperature value then adds this value to an array.</li>
<li>Writes out average temperature from the array on each interation</li>
</ul>


Instructions  (You can either work on your laptop and build the solution then deploy to you Raspberry PI or you can develop on the Rapberry PI. The PI will contain NodeJs and NPM)
1. Ensure you have node and npm installed on your machine  https://nodejs.org/en/ (When you install node you will get both node and npm)
2. Ensure client application is installed and started that is located in the https://github.com/spock75/node-iot-client-dm.git repository
3. Download and unpack zipped file of application or clone respositoryusing git clone
4. Open terminal window to the location where the project files are located
5. Type "npm install"
6. Edit the CallMethodOnDevice.js and update the connection string to the IoT Hub and Device ID with the provided connection string/DeviceID in Hackathon instructions
7. After all packages are installed type "node CallMethodOnDevice.js" to run application
