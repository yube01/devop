
docker build -t reactjs .
docker run -d --rm -p 5555:8000 --name myreactapp reactjs