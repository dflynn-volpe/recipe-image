# recipe-image

Application for a Recipe website -> finds other recipes with similar rare ingredients


Git clone 

Cd files

podman build --tag python-podman . 

podman run --publish 5000:5000 python-podman

(outside container): (inside container)

http://127.0.0.1:5000

- Aine Keenan

  

Here is a simple Flask web application that uses HTML templates.

To enjoy the application, follow these simple steps:

-Find a URL that holds your latest recipe!
-Paste the URL into the search bar of our web application
-(Optional) If you have dietary restrictions, select them now
-Enjoy a list of tasty new recipes that share similar uncommon ingredients

To run the application outside of podman, follow these simple steps:

-Download the dependencies needed with pip install -r requirements.txt
-Clone the repository in a directory of your choice
-Run the application on a local host. Default port 5000
-Command to run application: python app.py or python3 -m flask run
-Watch the magic happen!
