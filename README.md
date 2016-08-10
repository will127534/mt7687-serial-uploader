##MT7687 Serial Uploader  
this uploader is using xmodem to upload the bin file to MT7687  

#Usage 
'
  -f BIN_PATH   path of bin to be upload  
  -c COM_PORT   COM port, can be COM1, COM2, ..., COMx  
''
#Example  
python .\upload.py -c com24 -f ./gpio_configure_pull_state.bin  
