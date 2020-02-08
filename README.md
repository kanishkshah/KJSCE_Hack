# StartIt

The project aims at providing innovative solution for the investors to find potential Startups

## Technology Stack
 
 1. Django for backend framework
 2. Html5,CSS,Bootstrap and Javascript for frontend templating
 3. SqLite3 for Database 
 4. Selenium for Web Scrapping 

## Build Instructions
 
 ### 1. Clone the repository locally :
 
 ```
 git clone https://github.com/kanishkshah/KJSCE_Hack.git
 ```
 
 ### 2. Setup a virtual environment :
 
 ```
 python3 -m venev myenv
 ```
 
 ### 3. Activate source :
 
 ```
 source myvenv/bin/activate
 ```
 
 ### 4. Install all the requirements 
 
 ```
 pip install -r requirements.txt
 ```
 
 ### 5. Make migrations :
 
 ``` 
 python manage.py makemigrations
 ```
 
 ### 6. Run migrations : 
 
 ```
 python manage.py migrate
 
 ```
  ### 7. Run Selenium Server on a seperate terminal :
 
 ```
 DISPLAY=:1 xvfb-run java -jar ~/selenium/selenium-server-standalone-3.141.59.jar
 ```
 
 ### 8. Run the server locally :
 
 ```
 python manage.py runserver
 ```
 
 The project is live on localhost : 8000
 
## Contributing
  
   1. Fork it (https://github.com/kanishkshah/KJSCE_Hack/fork)
   2. Create your feature branch  (```git checkout -b feature/fooBar```)
   3. Commit your changes (```git commit -m 'Add some fooBar'```)
   4. Push to the branch (```git push origin feature/fooBar```)
   5. Create a new Pull Request
  
