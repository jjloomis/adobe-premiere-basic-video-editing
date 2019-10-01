# Creating and working with proxy files

Proxy files are compressed versions of your project's uncompressed media files. After creating proxy files, you can toggle your project's timeline to reference these compressed files instead of your original uncompressed files. Doing this will make the editing process run smoother as proxy files use substantially less bandwidth than uncompressed files.

## Downloading JAMS Proxy File Settings

**Note**: Use Chrome as your browser when downloading files. Safari can [cause unexpected behavior](/troubleshooting/computer-is-trying-to-open-jams-text-template-in-photoshop.md) to occur when used to download files.

1. **Control-click** this link: [JAMS-Proxy-File-Settings.epr](https://jams-downloadable-files.s3-us-west-2.amazonaws.com/templates/JAMS-Proxy-File-Settings.epr). In the fly-out menu, select **Save Link As**.
2. In the Save As box, navigate to and select your project folder.
3. Click **Save**. The JAMS-Proxy-File-Settings.epr file will download to your project folder.

## Creating proxy files

1. In Premiere, go to and select the Project pane \(lower right.\) Note: When selected, the Project pane will appear surrounded by a blue line. 
2. Press Command-A \(on keyboard\) to select all of the files in the Project pane. 
3. Control-click one of the selected files in the Project pane. In the fly-out menu, select Proxy and then choose Create Proxies. A Create Proxies box will appear. 
4. In the Create Proxies box, click Add Ingest Preset. 
5. Navigate to your project folder and select JAMS-Proxy-File-Settings.epr. Click Open. 
6. In the Create Proxies box, click OK. Adobe Media Encoder will open and create the proxy files. **Note**: This process will probably take a fair amount of time to complete.  

## Caffeinating your Mac

To prevent your Mac from logging you out \(and disrupting the proxy file creation process\), you can caffeinate its screen.

1. Click the Desktop to enter Finder mode. Then go to Go on the menu bar. Select Utilities.
2. In the Utilities window, select Terminal. A terminal window will appear.  
3. Enter the following text in the terminal window: `caffeinate -d`
4. Press Return \(on keyboard.\) The terminal prompt will move to a new line. Your Mac is now caffeinated. 
5. To stop caffeinating your Mac, bring up the terminal window again and press **Control-C** \(on keyboard.\)

## Using proxy files

When you activate the Toggle Proxies button, the Timeline will reference your project's proxy files during the editing process.

1. In the Program pane \(upper right\), click the Button Editor button \(plus sign button in lower left corner of Program pane.\) The Button Editor panel will appear. 
2. Click and drag the Toggle Proxies button into the Program pane's toolbar \(bottom of Program pane.\) Click OK when finished. The Toggle Proxies button will appear in the Program pane's toolbar. Note: You will need to do this every time you use a new computer. 
3. Click the Toggle Proxies button. The Toggle Proxies button will appear blue. Your project's Timeline is now referencing the proxy files in your project folder. 

![](/assets/adding-toggle-proxies-button.png)

