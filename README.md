# SonicOSBulkObjects

By J Tannerman

SonicOSBulkObjects is a project I started for my own use to streamline the repetitive task of adding address objects to SonicWALL UTM appliances.  
This project was developed and tested for use with SonicOS API on Gen 7 UTM appliances. 

This was made for my own use, and it does a specific thing that is useful to me.  
I am not a software dev, I am an IT guy.  IT guys write crappy code, and I am no exception. 

If you find it useful, please use it totally at your own risk.  It is a quick tool I made for myself. If it helps others, that is cool. 
No warranty whatsoever. I make no representation that this will work properly, or at all.  If this script bricks your SonicWALL somehow, kills your computer, or steals your children, I am not responsible. 

Resources in this project:

snwl-add-objects.ps1  ------ This is a PowerShell script that takes a CSV file and generates API requests to a Gen 7 SonicWALL to add address objects

test-import.csv   ------- This is a sample CSV file with some fake, but valid, address object data in it.
