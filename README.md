# Movietrailer
   Movie tariler application allows the user to disply his/her favourite movies in the webbrowser. The server side coding
   helps to do this in an easier way.Implemented using python shell python 2.7.11
# The mainclass >Movietrailer
  The base class movietrailer is created and can be reused for the different child classes.
  **import package webbrowser
  The favourite moives are going to be displayed in weebroswer.
  **define __init(self,param)**
  The init function will be the first function to be executed.The self refers to itself and Param may contain either 
  one to many or no parameter.
  For example:
  define __init__(self,movietitle,movietrailer)
  **define requiredmethod()**
  The user can define their own methods.This method can be accessed using calssname followed by method name.
  For example:
  define show_trailer(self)
  This method action is defined by it's name. The show trailer implies when it is executed it will show the user favourite
  movie trailer.
  
# The subclass
  This class will import the functionalities defined at base class.The other packages/class can also be imported.
  This can be done by using the "import" at beginning of the program.
  For example:
  import baseclass __This name is same as the name given to the base class program__
  **calling the function in base class**
  The function defined inside the base class is called using the file name followed by the class name and it's parameters.
  For example:
  The baseclass has the class name base and the method name as __init__ followed by the parameters movie_title,
  movie_storyline
  movietrailer.base(italian_job,"hijack")
  **Displaying the favourite movie using HTML file**
  The movies will be stored in an array list and passed as parameter to the script file.
  For example:
  movies = [italian_job,ice age2] and scripting python file name as apple then,
  apple.open_movie(movies) __the open_movies is the method inside script file__

#License
  normalize.css v3.0.3 | MIT License
  
  

