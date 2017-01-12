		
#Saurabh Vashisth

------------------------------------------------------------------------------------------------
IT IS RECOMEMDED TO READ THE README BEFORE RUNNING THE SERVER/CLIENT  
------------------------------------------------------------------------------------------------

 **INDEX**  

1. COMMANDS
2. HOW TO RUN  

------------------------------------------------------------------------------------------------
1. COMMANDS  
------------------------------------------------------------------------------------------------

	1. IndexGet longlist   
	   To see the entire listing of the shared folder/directory including name,size,timestamp 
	   and type of the files.  
	2. IndexGet shortlist "startTimeStamp" "endTimeStamp"  
	   To see the names of all the files created between the start and end timestamps.  
	3. FileHash verify "filename"  
	   Returns MD5 checksum and last modified timestamp of the file.  
	4. FileHash checkall  
	   Returns name,checksum and last modified timestamp of all the files in the shared directory.  
	5. FileDownload "filename"  
	   Download files from the shared folder of connected user to our shared folder.  
	   It returns name,size,last modified timestamp and the MD5 hash of the requested file.  
------------------------------------------------------------------------------------------------
2. HOW TO RUN  
------------------------------------------------------------------------------------------------
	
	1. Run the commands "python server.py" and "python client.py" on different terminals.  
	2. Run the server before running the client.  
