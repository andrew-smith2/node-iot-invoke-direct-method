# Node-iot-device-caller
Simple node IOT device client
<br>
<ul>
<li>Sets up a calling application that registers application with the IOT hub and makees direct method call to a device</li>
<li>Takes returned payload which contains a temperature value and adds to an array.</li>
<li>Writes out average temp in the array on each interation</li>
</ul>


Instructions
1. Ensure client application is installed and started that is located in the https://github.com/spock75/Node-Iot-Client.git repository
2. Ensure you have node and npm installed on your machine
3. Download and unpack zipped file of application or clone respository 
4. Open terminal window to the location where the project files are located
5. Type "npm install"
6. After all packages are installed type "node CallMethodOnDevice.js"
