# TechTreds Web Application

This is a Flask application that lists the latest articles within the cloud-native ecosystem.

## Run 

To run this application there are 2 steps required:

1. Initialize the database by using the `python3 init_db.py` command. This will create or overwrite the `database.db` file that is used by the web application.
2.  Run the TechTrends application by using the `python3 app.py` command. The application is running on port `3100` and you can access it by querying the `http://127.0.0.1:3100/` endpoint.

### Application [Source](https://github.com/udacity/nd064_course_1/tree/main/project/techtrends)