# Huffman-Coding
Its compression technique which can reduce the size of message or file. 


Procedure to encode and decode the file:

step 1) create the executable file named as say encode of encode.cpp and huffman.cpp by following command->
g++ encode.cpp huffman.cpp -o encode

step 2) now compress the .txt file to encrypted file usinf encode.exe file
./encode input.txt encryptedFile.huf

step 3) now we will create decoding executable file named as decode (which will act as a decrypting key) 
g++ decode.cpp huffman.cpp -o decode

NOTE -encrypted file will be nearly of half size and we also have decreptying key as well which we can send over the network and save the 
network bandwidth

step 4) now we can decode the file using followinf command 
./decode encryptedFile.huf output.txt
(no need to already keep output.txt file, even if it present its ok)