# Image Frequency Analysis

This package is build to combine all the steps that are done as part of the
frequency analysis using the Fourier transform approach.



## Install the Package
You can install the package using the pip command

`!pip install image_frequency_analysis` - when installing through jupyter notebook

`pip install image_frequency_analysis` - when installing through a command prompt


## Using the package
Once you have installed you can use the package by importing the image_frequency_analysis method from the package

` from image_frequency_analysis import image_frequency_analysis as ifa `

You can then pass the image path to the function which is a required argument, to get the plot 
of comparison between the original image and the filtered image

**Example:**

` ifa('sandstone.tif') `

**Sample Output:**

![image](https://user-images.githubusercontent.com/51501788/233843791-a3fc6c79-ea7f-43ed-8e13-da91caf21749.png)


By default the package uses the high pass filter to perform the filtering of the image. This option can be overridden using
the optional parameters that can be sent to the function.

You can find the various optional parameters and their usage in the package using the help command.

` help(ifa) ` or `help(image_frequency_analysis`


For request of any new feature or an issue please raise an issue
with the appropriate label as Bug or Enhancement - [Raise Issue](https://github.com/thivagar-manickam/image_frequency_analysis/issues)
