# MotionDetector
Project based on tutorial from pyimagesearch.com to use Raspberry Pi as surveillance camera

Followed this tutorial: http://www.pyimagesearch.com/2015/06/01/home-surveillance-and-motion-detection-with-the-raspberry-pi-python-and-opencv/

Using Raspberry Pi 2, Raspbian Jessie, with Raspberry Pi Camera

Updated code for DropBox API v2. Also added feature to send motion captures via email. 



Run following code to activate correct virtualenv: 
source ~/.profile
workon cv

Run following code to check if Python script is running:
ps aux | grep python

Run following code to execute Python script:
python pi_surveillance.py --conf conf.json
