# Mayo-Detector

After creating the logistic regression to identify cats, I realised i can make one to detect my cat from the others

I started with collecting photos of my cat, about 400. Now i would say this is harder than the code as my cat would not stay still :)

i then got 400 more photos of other cats from datasets available online

Processing the data was the first step

I wrote a code to collect photos form both the folders and combine it in another while resizing it to 128x128 pixels, this thought me a lot about the OS, Pandas, opencv libraries and sci-kit available in python

i used the OS library to combine the photos from both the folders, followed by using the Dataframes in the pandas library to create path and labels for that path then shuffled the photos with it labels so we can have a random sequnce of mine and the other cats photos for the algorithm ill be using.

We then took that dataset and used opncv to resize the images to 128x128 and stored it another csv file

The sci-kit library was useful to creat the tran, validation and test split, we used a 70% training, 15% validation and 15%testing datasets from it 
