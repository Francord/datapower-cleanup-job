IBM DaPower Gateway Expired Certificate Clean Up Script



1. Attached is the PowerShell script to remove the expired certs on IBM DataPower Gateway. You must use version 7.3.5 and above(the latest version is recommended). If you are not sure about what version you have, you can run the following command "$PSVersionTable".

2. The file can be saved as deleteExpiredCerts.ps1

3. Run the following command "Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass" in the terminal before you run the script.


4. To run the script, make sure you're in the same directory of the file and type the following command: ./deleteExpiredCerts.ps1

5. Follow the prompt and enter the required information


Francis Cordor 


https://francordsoft.com/
