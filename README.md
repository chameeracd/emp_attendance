# emp_attendance
## Installation

First, open a command console, enter your web root directory and
execute the following command(s)

    git clone git@github.com:chameeracd/emp_attendance.git
    cd emp_attendance
    composer update
    
change `.env` for database config

    php app/console doctrine:database:create
    php app/console doctrine:schema:update --force
    
    php bin/console server:run


## Usage
goto `http://127.0.0.1:8000`
