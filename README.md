# RoundHashFunction-v2-
Second version of hash function with new additionals  
HeaderHash.h hasn't changed  

Enter input text, salt, hash lenghtand quantity of rounds : string10 salt 10 5  
TMNXhTLLwd  
xxwpvYQwQd  
gDzQXQVXnU  
G1xNcxpXPU  
gNPOy11XQU  
Final hash - r1TpDtDXlU  

This is how it works:  
text + hash = hash1  
salt + hash = hash2  
-------------------  
hash1 + hash2 = hash3  
hash3 + hash2 = hash4  
hash4 + hash3 = hash5  
...
