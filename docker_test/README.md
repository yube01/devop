
docker build -t reactjs .
docker run -d --rm -p 5555:8000 --name myreactapp reactjs


docker tag [image-name]:tag [yube001/image-name]:tag

docker push yube001/image-name:tag