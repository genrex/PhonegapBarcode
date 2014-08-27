Created a small app last night to read barcodes.

 

Nothing fancy. Just a button to invoke the barcode reader camera and then returns the barcode number along with the barcode standard.

 

You can get it here:

https://build.phonegap.com/apps/1065666/install/?qr_key=UPYa4xMs3xX3aDY_9bfn

 

Checked on iPhone 5S and Android Kit Kat.

 

I am only using an html file and a js file along with the config.xml.

 

You can get the code from my github repository. You can remove the resource files from config.xml. I just got it from the base template.

 https://github.com/genrex/PhonegapBarcode

 

Instructions:

 

To add the plugin , in Config.xml you need to have:
<gap:plugin name=”com.phonegap.plugins.barcodescanner”/>