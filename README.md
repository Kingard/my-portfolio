## A personal portfolio website

 This is a personal website that shows my skills, career interests and some projects I've 
worked on.

## Database 

*sqlite*


## Discretionary  Access Control

From the admin end, I am able to add and update information on the website


##Installing Dependencies

#### Python 3.7

As provided here, install the latest version of python [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)


#### Establish a virtual Enviornment

Virtual environments provide a decent level of modularity for projects making a developer able to distinguish one project from another.
It also houses the dependencies for the project. Instructions for setting up a virual enviornment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### PIP Dependencies

Install dependencies via the provided `requirements.txt` file

```bash
pip install -r requirements.txt
```

This will install all of the required packages we selected within the `requirements.txt` file.


### Error Handling
Errors are returned in JSON format, objects with "success" set to False, "error" set to the error code along with 
the corresponding error message.

Possible errors:
- 400: Bad Request
- 403: Forbidden
- 404: Resource Not Found
- 422: Request can not be processed
- 500: Internal Server Error



## Running the server


To run the server, execute:

```
python manage.py runserver
```
