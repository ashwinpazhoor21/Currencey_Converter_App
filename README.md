# Currency Converter

## Description

This Currency Converter web application converts US dollars to popular currencies and displays historical exchange rates. It features a responsive design, adjusting the size and number of data points on the graph based on screen width. A CSS animation enhances the user experience when viewing the currency exchange graph. Real-time exchange rates are fetched using an API, and the JavaScript implementation leverages modern techniques like promises.

### File Structure
- **.vscode**: Contains configuration files for running the project in Visual Studio Code.
- **currency**: Includes Django-related files, such as:
  - **\_\_pycache\_\_**, **migrations**, **static**, **templates** folders
  - **models.py**: Defines the form model for currency conversion.
  - **forms.py**: Creates a form based on the model.
  - **views.py**: Defines the application's routes and logic.
  - **currency.js**: Fetches currency data and renders the graph.

- **migrations**: Contains migration files for database schema changes.
- **static**: Includes static files like **canvas** folder, **currency.js**, **favicon.ico**, and **templates** with HTML files.
- **templates**: Contains the **index.html** file for the application.

- **db.sqlite3**: The database file storing graph data and application permissions.
- **manage.py**: The main file to run the project (`python3 manage.py runserver`).

## Reflection

This project was a valuable learning experience, as it involved integrating real-time data through APIs and utilizing advanced JavaScript techniques. The responsive design and interactive graph enhanced the user experience, showcasing the importance of front-end optimization. Developing this application provided a deeper understanding of Django and modern web development practices.