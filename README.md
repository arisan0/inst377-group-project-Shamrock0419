# inst377-group-project-Shamrock0419
inst377-group-project-Shamrock0419 created by GitHub Classroom

Name: FoodFacts

Description: In response to the growing need for transparent and comprehensive information on food products, we propose the development of the Food Facts Platform(FFP). The FFP aims to empower individuals to make informed dietary choices by providing a centralized and accessible source of detailed information regarding the food products they put into their system. The FFP aims to go beyond the limitations of traditional nutrition labels by offering a holistic view, including not only nutritional facts but also all the ingredients and where they originated, allergens, consumer-relevant labels, and environmental impact metrics, such as carbon footprint.

Target Browsers: this application is designed to be compatible with modern web browsers and should work with Google Chrome, Safari, Microsoft Edge, etc.
Compatibility on both iOS and Android Devices is expected.

User and Design Manual Below.


# Developer's Manual 
Installation: make sure to have the IDE Visual Studio Code installed on your system
  - copy the repository code name and prepare your Visual Studio
  - open a new terminal by using the terminal category on VS Code and clicking "New Terminal"
  - clone the repo by typing in git clone {in here should be the repository code name you copied from github}
  - once cloned, open the file folder in your VS Code
  - after you clone the repo, install dependencies with the command: npm i
  - to run a rough version of the web application, you can open it live by clicking "Go Live" at the bottom right
  - to start the web application and get full effects, run the command: npm start
  - to end the web application session, press CTRL + C in your terminal

API: This application fetches data from the Open Food Facts data API and is only given access to a limited amount of products
  - utilizes a GET request to `https://world.openfoodfacts.org/api/v2/search` to retrieve product information based on a user product search

Known Bugs: 
  - no known bugs have been reported as of now

Future Development:
  - looking to enhance the user interface, making it more user-friendly and appealing
  - plan on adding sorting and filtering features to minimize searches
  - want to expand the options and open up the limitation of products for there to be a wider range of product facts available for users
  - looking to address the organization problem, nutrition, and product facts are not visually organized and appealing


