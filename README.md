# Movietrailer
   Movie tariler application allows the user to disply his/her favourite movies in the webbrowser. The server side coding
   helps to do this in an easier way.Implemented using python shell python 2.7.11
## The mainclass > Movietrailer
  The base class movietrailer is created and can be reused for the different child classes.
  **import package webbrowser**  
  The favourite moives are going to be displayed in webbroswer.This package allows user to enter his/her favourite movielinks   into the code.The link is given below on how to use webbrowser packages.
  **https://docs.python.org/2/library/webbrowser.html**  
  
  **define __init(self,param)**  
  The init function will be the first function to be executed.The self refers to itself and Param may contain either 
  one to many or no parameter seperated by comma's.
  For example:
  define __init__(self,movietitle,movietrailer)  
  The movietitle and movie trailer parameters are passed to display the respective movietitle and movietrailer.
  
  **define requiredmethod()**  
  The user can define their own methods.This method can be accessed using calssname followed by method name.
  
  **Class name.Method_name**  
  For example:
  define show_trailer(self)
  This method action is defined by it's name. The show trailer implies when it is executed it will show the user favourite
  movie trailer.
  
## The subclass

  This class will import the functionalities defined at base class with additional features in case it is required.The other   packages/class can also be imported.
  This can be done by using ** "import classname/package name"** at beginning of the program.
  
  For example:
  import baseclass __This name is same as the name given to the base class program__
  #calling the function in base class  
  
  The function defined inside the base class is called using the file name followed by the class name and it's parameters.
  **mainclass.method_name(parameters_seperated_by_commas)**
  For example:
  The baseclass has the class name base and the method name as __init__ followed by the parameters movie_title,
  movie_storyline
  movietrailer.base(italian_job,"hijack")
  **create list of movie name's**
  The list is the collection of elements and enclosed within '[]'bracket's.
  The simple list is created as follows:
  **list_name=[list_of_elements]**  
  For example:
  In this project the movielist is created
  movies=[sun_rise,italian_job],the movie list is created.
  
  **Displaying the favourite movie using HTML file ** 
  The movies will be stored in an array list and passed as parameter to the script file.
  The script files imports the required package to display the list in webbrowser.The movies are arranged in an order and 
  required style using the HTML.
    **http://www.w3schools.com/html/**   is the link to basics of HTML.
  For example:
  movies = [italian_job,ice age2] and scripting python file name as apple then,
  apple.open_movie(movies) __the open_movies is the method inside script file__

##License  
normalize.css v3.0.3 | MIT License
