# Vehicle Catalog Management System

A desktop-based vehicle catalog application built with Python and Tkinter that allows users to browse, search, and manage vehicle listings through an intuitive graphical user interface.

## Features

### User Features
- User account creation and authentication
- Guest access mode
- Vehicle catalog browsing
- Vehicle search functionality
- Dynamic filtering by vehicle attributes
- Wishlist/Favorites management
- Vehicle image display
- Vehicle video previews
- Detailed vehicle information viewing

### Administrator Features
- Administrator authentication
- Vehicle catalog management
- Add new vehicle listings
- Edit existing vehicle information
- Remove vehicles from the catalog
- Manage catalog data persistence

### Catalog Data
Each vehicle record contains:
- Vehicle ID
- Make
- Model
- Year
- Color
- Number of Doors
- Number of Wheels
- Horsepower
- Vehicle Image
- Vehicle Video

## How to Download and Run:
For people who simply want to download and run the program:
1. Open your terminal
2. Navigate to your preferred directory
3. Clone the GitHub repository using `$git clone <repo_link>`
4. Open the newly created folder
5. Run the file `Front_Layout.py`

## How to Run the Build Script
To create an executable file for this program:
1. Open your terminal
2. Navigate to the directory of this program
3. Ensure the `Makefile` file is present in the folder
4. Run `make` in your terminal

You make need to install the following to run the MakeFile:
- `make`
- `PyInstaller`

Some useful commands:
Other commands:  
- `clean` remove built files  
- `rebuild` cleans, then builds

<b>Note: The build script will only run if all dependency have been installed on your desired python version. Currently, tkVideoPlayer is not updated for the latest version of python, as such this, build script requires python 3.10.9 in order for tkVideoPlayer to function.<b>

## Demo Recording
Below is a video showing the program run:

https://drive.google.com/file/d/14Wt1UVNjKmRpLT8uUcmc5woq4JcD7dqZ/view
