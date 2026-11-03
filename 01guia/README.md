docker build -t mysql-nuevo .

docker run -d -p 3306:3306 --name mysql-rejecutandose mysql-nuevo

