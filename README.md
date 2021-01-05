# airflow-speeltuin


Run once:

    docker-compose run webserver db init
    docker-compose run webserver users create -r Admin -u admin -e e.indarto@gmail.com -f admin -l user -p admin


Startup AirFlow

    docker-compose up



http://localhost:8080 (admin/admin)

http://localhost:5555