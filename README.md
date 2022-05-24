# Recipe API with Docker and Test Driven Development
With this api you can make a recipe using ingredients and tags from different models. You can also add images. I build this api with docker using test driven development, following pep8 guidelines.

Here you can test the api with swagger on the live server:

http://ec2-52-204-106-239.compute-1.amazonaws.com/api/docs/

1. You need to go to "/api/user/create/" and create an user:
![image](https://user-images.githubusercontent.com/56613216/170134876-daeafa58-1c2f-41bc-a7d9-f5b85925f9a0.png)

2. Go to "/api/user/token/" and get a token:
![image](https://user-images.githubusercontent.com/56613216/170135409-ed1a66e7-f87a-459d-b74f-7434bbb94bf7.png)


3. Type your token to the top right "Authorize" button's "tokenAuth (apiKey)" section. With "Token" in front like this:
![image](https://user-images.githubusercontent.com/56613216/170135679-142b2fb4-ac87-495d-9ce5-0b6278f390ac.png)

You are ready to test the api!
