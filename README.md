Run EPS_Test.py with the relevant function commented out to perform the procedure

To update software run EPS_Test.py with the Enter BSL Mode commented in
Then run bsl-scripter with the script_FRxx_uart.txt script
needs to be setup to have UART access through ttyS2 in CDH
Baud needs to be 115200 for EPS_Test.py and 9600 for Scripter
Obtain BSL Scripter for appropriate platform through TI's website

socat should be able to be used to bridge the UART to another computer from CDH
