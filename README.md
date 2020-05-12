# pitch-app

## Author

[Dan_Njoroge](https://github.com/greatdaniels)

# Description
This is an application that allows users to view quick pitches from different categories. The users can sign up and log in to access functionalities including: the ability to comment on a pitch, upvoting or downvoting a pitch, as well as creating a pitch in a specific category.

## User Story

1. Comment on the different pitches posted py other uses.
2. See the pitches posted by other uses.
3. Vote on s pitch they have viwed by giving it a upvote or a downvote.
4. Register to be allowed to log in to the application
5. View pitches from the different categories.
6. Submit a pitch to a specific category of their choice.

## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
  git clone https://github.com/greatdaniels/pitch-app.git
  ```
2. Move to the folder and install requirements
  ```bash
  cd pitch-app
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3.6 manage.py server
  ```
5. Testing the application
  ```bash
  python3.6 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.6](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)


## Known Bugs
* Pull requests are allowed incase you spot a bug.

## License
[MIT LICENSE](./license)