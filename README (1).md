
# Movie Recommender System Using Python and Flask

Content-Based-Movie-Recommender-System-using-Flask

This application provides recommendation of movies in user interest. It will record the feedback from user and will provide the similar interest of movies in return.

Check out demo: https://movie-recommender-sys-ritesh.herokuapp.com/

The details of the movies(title, genre, Keywords, Ovrerview, Cast, Crew etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the TMDB id of the movie in the API.

## API Reference

How to get an API.

Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.



  
## Lessons Learned

Similarity Score :

How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

More about Cosine Similarity : Understanding the Math behind Cosine Similarity


## Deployment

To deploy this project on Heroku


Install the Heroku CLI
Download and install the Heroku CLI.

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login

Clone the repository
Use Git to clone movie-recommender-sys-ritesh's source code to your local machine.  

$ heroku git:clone -a movie-recommender-sys-ritesh

$ git add .

$ git commit -am "make it better"

$ git push heroku master

Now wait for few minutes and click on View buttom genereated there.

Great!!! You are done. 
## Installation


Jupyter Noebook

PyCharm

Python

Numpy

Pandas

Scikit Learn   

Streamlit Framework
## Demo

Click on the below link to check out Demo

https://movie-recommender-sys-ritesh.herokuapp.com/

  
## Run Locally

Clone the project

```bash
  git clone https://github.com/ritesh1000/Recommender-System-for-Movies.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  pip install
```

Start the server

```bash
  python app.py
```

  
## How to run the project?

Follow the below instructions to run the project:

Clone or download this repository to your local machine.

Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt

Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)

Open your terminal/command prompt from your project directory and run the file main.py by executing the command python app.py.

Go to your browser and type http://127.0.0.1:5000/ in the address bar.
Hurray! That's it.

  
## Environment Variables

If you are using Pycharm to run this project. Then you will need to add the following environment variables to your .env file

`C:\Program Files\JetBrains\PyCharm Community Edition 2021.2.1\bin`

`C:\Program Files\JetBrains\PyCharm 2021.2.1\bin`

  
## 🚀 About Me
I'm a aspiring Data Scientist, Statistician and Machine Learning Programmer....

  