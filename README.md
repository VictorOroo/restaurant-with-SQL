# Phase-3-week-3-code-challenge
# RESTAURANT WITH SQLALCHEMY

For this assignment, we'll be working with a restaurant review domain.

We have three models: `Restaurant`, `Review`, and `Customer`.

 

For our purposes, a `Restaurant` has many `Review`s, a `Customer` has many

`Review`s, and a `Review` belongs to a `Restaurant` and to a `Customer`.

`Restaurant` - `Customer` is a many to many relationship.

 

**Note**: You should draw your domain on paper or on a whiteboard _before you

start coding_. Remember to identify a single source of truth for your data.

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

**Before you submit!** Save and run your code to verify that it works as you expect. If you have any methods that are not working yet, feel free to leave comments describing your progress.