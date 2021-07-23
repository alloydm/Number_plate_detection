# Vehicles Number Plate Detection Using Pytesseract
A system which uses the image of vehicles that break traffic rules (images of vehicles are captured by cctv camera) to detect and extract the number from the number plate and send it to the police department to get the information of the vehicle owner.
# Project 
### Install
If you are running this file in [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index) then skip this installation. 
This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Pytesseract]()

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 

### Code

Template code is provided in the `untitled0.ipynb` notebook file. You will also be required to use the included `wpod-net.json`and the `local_utils.py` python file to complete to successfully complete the project. 

### Run
If your are running in [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index) run it directly.

In a terminal or command window, navigate to the top-level project directory `Number_plate_detection/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook untitled0.ipynb
```
This will open the Jupyter Notebook software and project file in your browser.
## Screenshots

### Captured Image
![](https://github.com/nagendram399/Number_plate_detection/blob/main/Images/india_car_plate.jpg)

### Extracting only license plate
![](https://github.com/nagendram399/Number_plate_detection/blob/main/Images/Licenseplate.jpg)
### Preprocessed image
![](https://github.com/nagendram399/Number_plate_detection/blob/main/Images/preprocessedimage.jpg)
### Email sent through smtp server
![](https://github.com/nagendram399/Number_plate_detection/blob/main/Images/Emailscreenshot.png)

