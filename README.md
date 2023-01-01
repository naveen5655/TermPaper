# TermPaper
This dataset is part of my Term paper research on malware detection and classification using Deep Learning. 
It contains static analysis data (Top-1000 imported functions) extracted from the 'pe_imports' elements of Cuckoo Sandbox reports.
PE malware examples were downloaded from virusshare.com.
PE goodware examples were downloaded from portableapps.com and from Windows 7 x86 directories
## Features
- Column name: hash
- Description: MD5 hash of the example
- Content: 32 bytes string
##
Column name: GetProcAddress 

Description: Most imported function

Content: 0 (Not imported) or 1 (Imported)
##
Column name: ExitProcess

Description: Second most imported function

Content: 0 (Not imported) or 1 (Imported)
##
Column name: LookupAccountSidW

Description: Least imported function

Content: 0 (Not imported) or 1 (Imported)
##
Column name: malware

Description: Class

Content: 0 (Goodware) or 1 (Malware)

## Thank you for visiting my repository
