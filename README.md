# LSB-Steganography
Hide messages as well as images within other message and images and be able to retrieve them.

In order to run the program make sure you have any Python 3.XX installed.

Argument Options:
-e Hide a string in an image 
-d Retrieve a string from an image 
-i Hide an image in another image
-u Retrieve an image from another image 

-All Argument Options Must Be Followed By An Image Filename or Path
-

1) Download the file and navigate to the respective folder.
2) Run the command "Python steg.py" followed by the respective commands found above.
3) You will be prompted to enter a message or another image filename (for the image include it's extension and its filepath if needed)
4) You will have your hidden message!

IMPORTANT:
When hiding images within another image you must make sure it fits as I haven't added a guard yet. You can do so by multiplying the size of your first image (W px * H px) and making sure its greater than the size image you want to hide multiplied by 24 (W px * H px * 24).
