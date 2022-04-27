# Turbocharged real-time search with Ruby on Rails 7
Adding basic search functionality to a Ruby on Rails app is not the toughest task in the book but when you think about it before hotwire.dev was around the process of making "live" search work was rather cumbersome.

# Improvment ideas

Obviously, this example is very very primitive. There is a ton we could extract and reuse on the controller front, not to mention the gnarly query we used to search bands. The front end is messy and could use a make-over. The list goes on.

Some recommendations to extend this further might be:

* Use something like pg_search for better search functionality and performance
* Extract more logic from the controller to be used for other types of turbo_frame requests. A lot of that logic could move to the ApplicationController and become near automatic based on the request
* Consider turbo streams as an alternative realtime updating mechanism.


## 🔗 [Demo](https://realsearchs.herokuapp.com/)


# Tech Stack
![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white)
![Rails](https://img.shields.io/badge/rails-%23CC0000.svg?style=for-the-badge&logo=ruby-on-rails&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
