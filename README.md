How to configure the ETH008 card in Loxone config?

1. download the VO_eth008.xml file and save it in the folder where Loxone keeps the defined devices. In my case, the folder is "C:\ProgramData\Loxone\Loxone Config 9.3\Templates\VirtualOut"

Start up your Loxone project en go to the virtual outputs of the loxone server. Click on the predefined devices and look for ETH008. Click on the device and you will see that it appears as ETH008 in you virtual outputs. Here you get a warning about the IP-address, your IP-address is likely not the same as mine. If you click on the virtual output ETH008, you can see in the properties of this card the local address: http://192.168.x.y
Change this address for the card that you want to address.

From this moment on you can use all 8 relay outputs in you configuration.

They can be used for lighting, heating, screens and so on...

Remember: max. 16A for each relay!

if you look for the card on internet, the are more sources, e.g. in Holland 
https://www.antratek.nl/8-relaismodule-ethernet-eth008
