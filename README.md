# Deep-Vision-Trading-Algorithm

This was created in Google Colab.
The algorithm makes use of computer vision to take screen captures of a candlestick chart, measuring it against the image repository used for this model. The image repository is located in a folder on my Google Drive, which is mounted in the first few cells.

I felt the need to mount the Google Drive because it's a Google service connecting to Google Colab, minimizing any possible risk of error.

If the image cannot make a prediction or capture a screenshot, it will return "Unable to make a prediction." The algorithm cannot be used outside of an environment that doesn't allow for screenshots and computer vision.

It is best to run the algorithm on TradeStation, a website that allows for testing of algorithms specific to computer vision.

To use this, download the image repository folder, upload it to your Google Drive, then copy and paste the folder path to the cell and you should be good to go.

Next steps for this project would be adding a cell to augment the images to further train the Neural Network.
