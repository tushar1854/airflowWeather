# Step 1

git clone https://github.com/tushar1854/airflowWeather.git

# Step 2

pip install apache-airflow

# Step 3

docker-compose up --build -d

wait for 2-3 minutes

# Step 4

go to http://localhost:8080/

# Step 5

username='admin'

Your password is at

cd .\airflow\
cat .\standalone_admin_password.txt

# Step 6

.\airflow\ (at this path)

mkdir dags

copy weather_dag.py

and past

.\airflow\dags

# Step 7

Go to admin -> connection -> add new connection

connection id = "weathermap_api"

connection type = "HTTP"

host = "https://api.openweathermap.org"

Save
