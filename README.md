                             ASSIGNMENT
            SECURITY MONITORING WITH SPLUNK
NAME:MUSTAPHA ADAMU GIDADO

1.	List out the IAM users that accessed an AWS service (successfully or unsuccessfully) in Frothly's AWS environment?
2.	What is the processor number used on the web servers? Answer guidance: Include any special characters/punctuation. (Example: The processor number for Intel Core i7-8650U is i7-8650U.)
                                                            ANSWER
E5-2676 v3
From: Intel® Xeon® CPU E5-2676 v3 @ 2.40GHz

3.	Bud accidentally makes an S3 bucket publicly accessible. What is the event ID of the API call that enabled public access? Answer guidance: Include any special characters/punctuation   
                                                             ANSWER                                                                                    
ab45689d-69cd-41e7-8705-5350402cf7ac
this event corresponds to a PutBucketAcl API call in AWS CloudTrail, where the bucket’s ACL was modified to grant access to the All Users publi group, making the bucket publicly accessible

4.	 What is the name of the S3 bucket that was made publicly accessible?
                                                              ANSWER
frothlywebcode
this was identified from the same AWS CloudTrail PutBucketAcl event that enabled public access, where the field request Parameters.bucket Name shows the affected bucket
 
5.	 What is the name of the text file that was successfully uploaded into the S3 bucket while it was publicly accessible? Answer guidance: Provide just the file name and extension, not the full path. (Example: filename.docx instead of /mylogs/web/filename.docx) 
                                                                ANSWER
The text file that was successfully uploaded while the S3 bucket was publicly accessible is:
test.txt


6.	What is the size (in mb) of the .tar.gz file that was successfully uploaded into the S3 bucket while it was publicly accessible? Answer guidance: Round to two decimal places.
                                                                 ANSWER
The size of the .tar.gz file that was successfully uploaded while the S3 bucket was publicly accessible is:
1.54 MB

7.	What is the short hostname of the only Frothly endpoint to actually mine Monero cryptocurrency? (Example: ahamilton instead of ahamilton.mycompany.com)
                                                      ANSWER
jefferson

This host is identified in the Frothly lab as the sole endpoint that executed Monero mining activity.


8.	What is the FQDN of the endpoint that is running a different Windows operating system edition than the others?
                                                      ANSWER
washington.frothly.local

This system stands out in the Frothly environment because it is running a Windows Server edition, while the other Windows endpoints are running Windows workstation editions (e.g., Windows 10)



                                                                    



   

  



