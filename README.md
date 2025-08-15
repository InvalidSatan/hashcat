-- Run Command Prompt as an Admin --
cd C:\Users\Public\Desktop\hashcat-7.0.0
hashcat.exe -m 0 -a 0 hashes.txt testlist.txt

-- Let the process finish --
hashcat.exe --show -m 0 hashes.txt

-- Output should look like --
5f4dcc3b5aa765d61d8327deb882cf99:password
