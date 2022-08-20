//first command to install flask
pip3 install flask

//second to install WT forms
pip3 install flask-wtf

// if some errors with email install
pip3 install email_validator

// work with SQL database(command to install)
pip3 install flask-sqlalchemy

// for working with SQL use
python3
    // flask_project the name of main file in project
    from flask_project import db
        db.create_all()