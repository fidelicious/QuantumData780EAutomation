# QuantumData780EAutomation
Automation scripts to automate the video output of the QuantumData 780E model via Serial control

# ----------------------------------------------------------------------------- #
# 																																							#
# Script will prompt user at beginning regarding which test to execute					#
# Script will output 1 video timing per prompt & create a report file						#
# Timings outputted are based on test being executed														#
#																																							  #
# QuantumData 780e Settings:																									  #
# Hardware: Direct Serial or USB-Serial Female-Female & Null Modem in between	  #
# Generator Preferences: Baud 9600, RS-232 Keypad Mode: OFF											#
# Software: Confirm port, prefer COM under '10' else will get weird issues			#
# if using Windows. This code can be edited to use /dev/tty# path for linux/Mac #
# Script will change the Video Interface depending on the test being ran 				#
# so be sure to have all Video Hardware connected before starting a new test 		#
# 																																							#
# - if script failing on Windows, might need to initialize connection via 			#
# RealTerm program, confirm prompt appearing, then close & re-run Script				#
# ----------------------------------------------------------------------------- #
