# IMAGE STEGANOGRAPHY
## Steps to run the code: 
1) Download and install python onto your system on the system you'll use to run the code.The link for downloading python can be found [here](https://www.python.org/downloads/).
2) Install [VScode](https://code.visualstudio.com/download), follow the installation instruction mentioned in their website.
3) Install the requirements mentioned in the 'requirements.txt' file , steps to install from packages from a requirements.txt file can be found [here](https://github.com/saitejapabbathi/IMAGE_STEGANOGRAPHY/blob/main/requirements.txt)
4) without changing the name of any folders, run the hiding text in image steganography.py file
5)
   1. press 1 to encode  
   2. press 2 to decode
   3. press 3 to compare the two new images with original image.
 
   
**Encoding:**

   1. After pressing 1, enter the image name with extension which is in Original_image folder.
   2. enter the secret message you want to hide.
   3. Encoding is done, images are stored in Encoded_image folder.
   
**Decoding:**
   1.  Press 2 after encoding is done.
   2. The text files which contain secret message for each algorithm are saved in Decoded_output folder. 
  
**Comparison:**
   1. press 3, after decoding is done.
   2. its shows the graph of MSE values for both algorithms, *close the graph to proceed next*.
   3. next it shows the graph of PSNR values for both algorithms, *close that graph also to run the remaining code*.
   4. *after closing the both graphs*, Comparison.xls will be created in Comparison_result folder which shows the MSE and PSNR values in a table.
