# Phase-3-week-3-code-challenge
# RESTAURANT WITH SQLALCHEMY

## Description

For this assignment, we'll be working with a restaurant review domain.

We have three models: `Restaurant`, `Review`, and `Customer`.

 

For our purposes, a `Restaurant` has many `Review`s, a `Customer` has many

`Review`s, and a `Review` belongs to a `Restaurant` and to a `Customer`.

`Restaurant` - `Customer` is a many to many relationship.

 



## Topics
 

- SQLAlchemy Migrations

- SQLAlchemy Relationships

- Class and Instance Methods

- SQLAlchemy Querying

 

***
## Instructions
Build out all of the methods listed in the deliverables.

The methods are listed in a suggested order, but you can feel free to tackle the ones you think are easiest. Be careful: some of the later methods rely on earlier ones.

**Remember!** This code challenge does not have tests. You cannot run `pytest`.

You'll need to create your own sample instances so that you can try out your code on your own. Make sure your relationships and methods work in the console before submitting.

You are also encouraged to use the `seeds.py` file to create sample data to test your models and relationships.

Writing error-free code is more important than completing all of the deliverables listed - prioritize writing methods that work over writing more methods that don't work. You should test your code in the console as you write.

Similarly, messy code that works is better than clean code that doesn't. First, prioritize getting things working. Then, if there is time at the end, refactor your code to adhere to best practices. 


**What You Need to Have**
You need to have migrations and models for the initial `Restaurant` and `Customer` models, and seed data for some `Restaurant`s and `Customer`s.

You will need to create the migration for the `reviews` table using the attributes specified in the deliverables below.

## Setup Requirements
   - Git
   - Github
   - Visiual studio Code

## Technologies Used

The following have been used on this project:

- Python 3
- SqlAchemy

## Project Setup
Clone my repository into your machine(git@github.com:VictorOroo/restaurant-with-SQL.git)
install dependencies by running the following
-  Pipenv install alembic
-  pipenv install Sqlachemy
-  Pipenv install Faker
-  Pipenv shell

 ## Support and contact details 🙂
To make a contribution to the code used or any suggestions you can click on the contact link and email me your suggestions.
- Email: victor.oroo@student.moringaschool.com

## License

Copyright (c) 2022 Victor Oroo.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files , to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.       
