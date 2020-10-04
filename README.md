# geodjangotemplate
### Install Python3, pip and virtualenv first
#### Skip this, step if you already have one

    sudo apt-get install python3
    sudo apt-get install -y python3-pip
    sudo apt install python3-virtualenv

### Create your virtual env
    virtualenv myenv
    source ./myenv/bin/activate
### Clone this repo
    git clone https://github.com/itskshitiz321/geodjangotemplate.git
#### Navigate to this repo 
    chmod +x <library.sh>
    ./library.sh
    ogrinfo --version
#### Change the GDAL verision in requirements.txt if your installed version is different from default one 
    pip install -r requirements.txt

### Download Postgres interactive installer



https://www.enterprisedb.com/downloads/postgres-postgresql-downloads




    sudo ./postgresql-10.14-1-linux-x64.run

### Install postgis extension as well from stack builder



#### Now change your username , password and db name in settings.py accordingly to your database
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
