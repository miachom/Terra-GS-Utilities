# Downloads from Terra

This describes how data files cans be downloaded from Terra using GS-Utilities. First you need access to Terra with your registered email for authentication

# Install GS utillity 

1. curl https://sdk.cloud.google.com | bash
2. Open a new bash shell in your terminal, or restart shell as exec -l $SHELL

# Points to remember
1. Make sure that gsutility and python have the same version. 
2. Check this by gsutil version -l and see if compiled crcmod is true/false [it should be true for the download to work]. I used miniconda for my donwload
3. Once this is set, download the desired file or folder from Terra using their instructions. In the following I have breifly described the steps.
4. Initialize GS utility from Google SDK.
5. Choose the steps and answer appropriately.
6. Check your project listings to set configurations of Google Cloud SDK to use.
7. Go to bucket details of the Terra data and click on for download. Either copy the clipboard and directly download it to your current working directory.

# Important Note
If the files are being downloaded as .gstmp instead of .bam or .cram, that means the files are corrupted. This is either due to improper installation of Google SDK cloud or gsutility and python not having the same version. 
