### Steps
1. Install Arduino IDE from microsoft store [From here](https://www.microsoft.com/store/productId/9NBLGGH4RSD8?ocid=pdpshare) or using browser.
2. Add the libraries (4 zips that are in this repository) in Arduino . Go to Sketch > Include Library > Add .ZIP library . Choose the zip file you just downloaded，and if the library install correct, you will see Library added to your libraries in the notice window. Which means the library is installed successfully.
3. open the **fingerprin_sensor.ino** file with arduino.
4. do the connections as in this [Image](https://how2electronics.com/wp-content/uploads/2019/01/fingerprint-attendance-circuit-diagram.jpg) (code from this website won't work just do the connection of this image). As Fingerprint sensor R305 is not available in the shop so i used R307 sensor. Its pin diagram is [This](https://www.circuitstate.com/wp-content/uploads/2021/05/R307-Fingerprint-Scanner-Pinout-2-800x602.png) . It will work correctly in case you dont have R305.
5. Upload the code in arduino and run.

### Working
We have used 4 push buttons which are used to control the system. The functions of each button are:
1. Register/Back Button – Used for enrolling new fingerprints or going back
2. Delete/OK Button – This Button is used for deleting the earlier stored fingerprint system as well as granting access as an OK selection.
3. Forward Button – Used for moving forward while selecting the memory location for storing or deleting fingerprints.
4. Reverse Button – Used for moving backward while selecting memory location for storing or deleting fingerprints.

Enrolling New Fingerprint: To enroll New Fingerprint Click on the Register button. Then select the memory location where you want to store your fingerprint using the UP/DOWN button. Then click on OK. Put your finger and remove your finger as the LCD instructs. Put your finger again. So finally your fingerprint gets stored.

Deleting Stored Fingerprint: To delete the fingerprint which is already clicked on DEL Button. Then select the memory location where your fingerprint was stored earlier using the UP/DOWN button. Then click on OK. So fingerprint is deleted.

Downloading Data: Simply click on Register/Back Button and reset the button together. the serial monitor will be opened.

### snapshot
![WhatsApp Image 2024-11-10 at 14 03 29_f0b7d277](https://github.com/user-attachments/assets/46b5bc61-741b-428c-8b89-27982c3d872c)
attendance output fom aruino:
![WhatsApp Image 2024-11-10 at 12 08 20_86c1c448](https://github.com/user-attachments/assets/7250c988-0ae4-4d28-8d84-17f5ff9f894f)
demo video:
https://github.com/user-attachments/assets/22046891-d256-4173-8fdf-2b5bf91fdc54

