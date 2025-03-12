======================================================================

            ||---->> Instructions for Hands On <<----||

======================================================================

The "Hands On" is a Python script developed in the Google Colab environment that implements functions for reading and analyzing data in tabular files, such as ".TSV" files. The script processes the data extracted from these files to generate statistical graphs based on the tables. Before running it, some preliminary checks must be made. Therefore, follow the procedure described below.

[ 1 ] - Check if the tables were created correctly.

     [1.1] - Check if the tables were saved in tabular format (.tsv).

     [1.2] - Verify that two tables were created, one for the content (train.tsv) and the other for data validation (validation.tsv).

     [1.3] - Check if the tables were correctly assembled based on the example below:

             "|title           |tags                                       |"

              |(object name)   |['characteristic-01', 'characteristic-02'] |

              

[ 2 ] - After downloading the "Hands On" file from GitHub, do the following:

   [2.1] - Locate the file on your computer, usually in the "Downloads" folder.

   [2.2] - Right-click the "Hands On.zip" file and select "Extract here."

   [2.3] - Locate the two tables created to use in the script.

   [2.4] - Hold the "CTRL" key and select both tables.

   [2.5] - With both tables selected, use the "CTRL + X" command to move both at once.

   [2.6] - After using the command to move the tables, open the folder that was previously extracted, the "Hands On" folder.

   [2.7] - With the folder open, paste both tables inside the folder using the "CTRL + V" command.

   

[ 3 ] - With all the necessary files ready for upload to Google Drive, do the following:

   [3.1] - Open the browser and log into the desired email account.

   [3.2] - Once logged in, open Google Drive.

   [3.3] - With the Google Drive page open, click on "+ NEW."

   [3.4] - After a small window opens at the corner of the page, click on "Upload Folder."

   [3.5] - Locate the "Hands On" folder on your computer and click on "Upload."

   

[ 4 ] - With the folder uploaded and the Google Drive page open, do the following:

   [4.1] - Open the "Hands On" folder in Google Drive.

   [4.2] - With the folder open, click on the "Hands On.ipynb" file to open it in the browser via Google Colab.

   [4.3] - With the file open, look for step 3 titled "Step 3: Importing and cleaning training and validation data files, with specified file paths for each dataset."

   [4.4] - After locating the step, look for the sentences highlighted in red to change the file paths.

           "train = read_data('/content/drive/MyDrive/hands/teste-02.tsv')"

           "validation = read_data('/content/drive/MyDrive/hands/teste-01.tsv')"

   [4.5] - Once you find the lines, simply delete the end of the path that would be ".../hands/teste.tsv" and replace it with ".../Hands On/(table_filename).tsv"

   [4.6] - After changing the file paths, use the "CTRL + 9" command to run the entire script.

