**Step 1** :Open .pcb file inside the project

**Step 2** Navigate to menu  File->Plot

**Step 3:**  This window opens up - generate drill file
![image](https://user-images.githubusercontent.com/32264646/65579476-6fc7d880-df95-11e9-93dc-900bc1a6fab7.png)

The image above shows the many different layers that are used in this example project. In general, there are only 10 layers that are required for PCB fabrication and assembly (paste layers not required for fabrication only):
Top Copper (Top) + Top Soldermask (F.Mask) + Top Silkscreen (F.SilkS) + Top Paste (F.Paste)
Bottom Copper (Bottom) + Bottom Soldermask (B.Mask) + Bottom Silkscreen (B.SilkS) + Bottom Paste (B.Paste)
Board outline (Edge.Cuts)
Drill file (not shown in image above)



**Note :** Make sure the Plot format is set to ‘Gerber’ and all the aforementioned layers have been selected. Next, you will click on the ‘Generate Drill File’ button. You will be using the default values here. Click on ‘Drill File’ or press enter to generate the drill file (see image below):


![image](https://user-images.githubusercontent.com/32264646/65579655-caf9cb00-df95-11e9-9b44-b75f0f5592ee.png)


**step 4:** Click on plot to generate a the gerber files

**Review gerbers**

Step 1: Open project window in kicad , click on the highlighted icon
![image](https://user-images.githubusercontent.com/32264646/65579826-21ffa000-df96-11e9-978e-eafe81e6b13a.png)
Step 2:  On the gerb viewer window , navigate to File > Load Gerber file
![image](https://user-images.githubusercontent.com/32264646/65580137-b9fd8980-df96-11e9-9a25-7e3f81186096.png)

Step 3 : Navigate to location of gerber creation
![image](https://user-images.githubusercontent.com/32264646/65580211-d994b200-df96-11e9-8e81-703c35f17e7c.png)

After successfull loading , you can view the pcb design

**Send to vendor**
Zip the files inside the gerber folder and send it to the vendor for fabrication

