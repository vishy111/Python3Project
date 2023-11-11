# Python3Project

The Project

Take a ZIP file of images and process them, using a library built into python that you need to learn how to use. A ZIP file takes several different files and compresses them, thus saving space, into one single file. The files in the ZIP file we provide are newspaper images (like you saw in week 3). Your task is to write python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza". This will test your ability to learn a new (library), your ability to use OpenCV to detect faces, your ability to use tesseract to do optical character recognition, and your ability to use PIL to composite images together into contact sheets.

Each page of the newspapers is saved as a single PNG image in a file called images.zip. These newspapers are in english, and contain a variety of stories, advertisements and images. Note: This file is fairly large (~200 MB) and may take some time to work with, I would encourage you to use small_img.zip for testing.

Here's an example of the output expected. Using the small_img.zip file, if I search for the string "Christopher" I should see the following image:

![Screenshot (104)](https://github.com/vishy111/Python3Project/assets/77464839/481e0205-e299-4740-884d-3d81439c93cf)

![Screenshot (105)](https://github.com/vishy111/Python3Project/assets/77464839/ae977b70-d645-4852-b92a-df285969d43a)

![Screenshot (106)](https://github.com/vishy111/Python3Project/assets/77464839/a03a048f-d338-4d3f-80b8-70f8c6fc519d)

![Screenshot (107)](https://github.com/vishy111/Python3Project/assets/77464839/79b8afb1-8502-4c38-947c-cbd34d9e902f)
