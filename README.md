# vehicle-registration-system
A part of the course OOAD &amp; SE at PES University. 

## Required Features according to the SRS provided.
- [x] Main Window and login
- [ ] New Vehicle Registration
- [ ] Transaction Records
- [ ] Temporary Vehicle Registration
- [ ] Search Vehicle Details
- [ ] Update details

## How to clone and run this?
First clone this repo using the below mentioned command. 
```
git clone https://github.com/vishnureddys/vehicle-registration-system.git
```
Now move into the directory. 
```
cd vehicle-registration-system
```
Create and start a virtual environment to avoid dependency issues. 
```
python -m venv env
.\env\Scripts\activate
```
Now install the dependencies using this command.
```
pip install -r requirements.txt
```
Now change to the directory containing the code.
```
cd src
```
Migrate and start the server.
```
python manage.py migrate
python manage.py runserver
```
