# emp_attendance
## Installation

First, open a command console, enter your web root directory and
execute the following command(s)

    git clone git@github.com:chameeracd/emp_attendance.git
    cd emp_attendance
    composer update
    
change `.env` for database config

    php bin/console doctrine:database:create
    php bin/console doctrine:schema:update --force
    
    php bin/console server:run


## Usage
goto `http://127.0.0.1:8000/employee/` for employee create
goto `http://127.0.0.1:8000/employee/attendance/` for employee attendance
