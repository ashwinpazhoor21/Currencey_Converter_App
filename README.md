# Currency Converter

Description:

This is a Currency Converter website/application.  
This app converts US dollars to popular currencies and displays previous exchange rates, it displays a graph of exchange rate over past year.
Size and number of data points change with screen width (mobile responsive). I also, have a nice css animation on my website when I pulls up the currency exchange graph. I used an Api for the exchange rate to be in real time.

The javascript is significantly more complex than previous projects. Including utilizing modern js techniques like promises.
Graph changes number of data points depending on the view width.

*.vs code*: This Folder contains the file that helps run the project through visual studio code editor(my code editor). 

*currency*: This folder contains some *_pycache_* files, the *migrations* folder, the *static* folder, the *templates* folder, and some other python files.

*migrations*: This Folder contains more *_pycache_* files, the *_init_.py* file, and the *0001_initial.py* file.

*static*: This folder contains the *canvas* folder, the *currency.js*, the *favicon.ico*, the *templates* folder with the html file for the entire application, and some other python files. 

*templates*: This folder contain the index.html file for the entire application. 

*Other Python Files*: The other python files below in the *currency* folder are all used to import the django aspects of the project. 

*models.py*: Creates a model for form with space to intput usd and currency to convert to.

*forms.py*: Makes a form based on model.

*views.py*: Makes a program for route.

*currency.js*: Gets currency data to make the graph.

*final*: This folder contains more *_pycache_*  files, and some other python files used to import the django aspects of the project. 

*db.sqlite3*: This is the file that contains all the graph data and the permissions for the application. 

*manage.py*: This is the main file that is used to run the entire project and I use the command "python3 manage.py runserver" to run the application.
