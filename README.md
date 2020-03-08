# Burp AlphaNumeric Intruder Extension
Contains burpsuite extension (using Python) which can used to intrude alphanumeric characters.

Burpsuite community edition doesn't have this feature and users have to enter all the alphanum characters to do an intruder attack.
This extension makes job easy to send all the alphanum characters. 
User can change/customize the payload per their requirements.

**How to ADD this extension?**

Copy this code and create a python file (ex - alphanum_burpextn.py)

At Extender / Options / Python environment, setup the Python Environment(Download file jython-standalone-2.7.1.jar and provide the path of it).

In the Extensions tab of the click "Add" to add Burp Extension.

Select Python as Extension type and select the path of the Python file created above.


**How to RUN this extension?**

If you are planning to do and Intruder attack, send the request to intruder and set the positions.

Select the Payload type as "Extension Generated".

Select the Generator name as per the Python file and you are good to go to do and intruder attack.














