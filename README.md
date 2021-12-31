# Image Steganography
***Steps to run the code:***
Download and install python onto your system on the system you'll use to run the code.The link for downloading python can be found here.
Install VScode, follow the installation instruction mentioned in their website.
Install the requirements mentioned in the 'requirements.txt' file , steps to install from packages from a requirements.txt file can be found here
without changing the name of any folders, run the hiding text in image steganography.py file
press 1 to encode
press 2 to decode
press 3 to compare the two new images with original image.
**Encoding:**

After pressing 1, enter the image name with extension which is in Original_image folder.
enter the secret message you want to hide.
Encoding is done, images are stored in Encoded_image folder.
**Decoding:**

Press 2 after encoding is done.
The text files which contain secret message for each algorithm are saved in Decoded_output folder.
**Comparison:**

press 3, after decoding is done.

its shows the graph of MSE values for both algorithms, close the graph to proceed next.
next it shows the graph of PSNR values for both algorithms, close that graph also to run the remaining code.
after closing the both graphs, Comparison.xls will be created in Comparison_result folder which shows the MSE and PSNR values in a table.
