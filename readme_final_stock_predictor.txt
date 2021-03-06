OUR ASSUMPTIONS:  OUT OF MONEY FOR COVERED CALL AND FOLLOWED BY A PUT:

Please follow our presentation file for our CALL and PUT considerations.

The implementation of the network and our reasoning behind how we suggested options is explained in our slides.

The code outputs a list of Option Suggestions based on model predictions for risk factors varying from 10-50%

Steps to implement:

1. The code impemented in Google Colab notebook is present in the folder "Chaitanya_Dylan_Jayashri" by the name "FinalStockPredictor.ipynb"

2. The training datasets by the name of F.csv and CVX.csv are present in the "Training Data" folder under "Chaitanya_Dylan_Jayashri"

3. Right click on the "FinalStockPredictor.ipynb" file, go to open with and select "Colaboratory".

4. The python notebook will open inside the Google colab platform.

5. A couple of steps to perform before you actually run the code.

   5.a. Make a foler by the name "BigData" inside your Google Drive and copy the training data files "F.csv" and "CVX.csv" to
		this folder.
   5.b. Now run, the first cell of the notebook. You should see a "play or run" icon on the left of the cell. Click on that.
		If you should receive a warning stating that this notebook was not authored by Google, just click on "Run anyway".
   5.c. Once, the cell starts executing, you will receive a link in the outputs section (just below the cell you are running),
		to get your "authorization code"
   5.d. Clicking on that link, will open a new tab in google chrome and you shall see your authorization code. Copy and paste
		that code into the rectangular box, in the outputs section of the cell you just ran and press enter. You should see the
		output change to "Mounted at content/drive"

6. The above step sets the environment with the correct paths and data files for the code to run.

7. Now, go to the second cell in the notebook. Go to Runtime, and click Run After or alternatively, you can go with "Ctrl+F10"
   This essentially runs, the current and all the other following cells, to give you the output. You should be able to the see
   the output of each cell, just below it.   

8. The code should execute within 15-30 mins and you will see the original stock data, the prediction for the last few days and a
   list of option suggestions with estimated gain and risk factor.

If you should run into any issues while running this program, email us for help.

for information:
Chaitanya: cbhure@uncc.edu
Dylan:  ddcruz@uncc.edu
Jayashri: jkethini@uncc.edu

