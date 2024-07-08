docker build -t yayahassid/flask-hello-app:latest .
docker push yayahassid/flask-hello-app:latest
kubectl apply -f k8s-deployment-service.yaml