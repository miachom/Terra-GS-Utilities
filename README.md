# Downloads from Terra

This describes how data files cans be downloaded from Terra using GS-Utilities. First you need access to Terra with your registered email

# Install GS utillity 

1. curl https://sdk.cloud.google.com | bash
2. Open a new bash shell in your terminal, or restart shell
exec -l $SHELL

# Points to remember
1. Make sure that gsutility and python have the same version. 
2. Check this by gsutil version -l and see if compiled crcmod is true/false [it should be true for the download to work]. I used miniconda for my donwload
3. Once this is set, download the desired file or folder from Terra using their instructions. In the following I have breifly described the steps.


