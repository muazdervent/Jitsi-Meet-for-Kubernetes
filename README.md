# Jitsi-Meet for Kubernetes

One pod Jitsi-Meet for Kubernetes cluster.


## Usage
Clone kubernetes repo.
```
git clone https://github.com/muazdervent/Jitsi-Meet-for-Kubernetes.git
```
Deploy Jitsi-Meet on your Kubernetes Cluster.
```
cd Jitsi
kubectl apply -f jitsi-deployment.yml
```
Go https://any-ip-on-cluster:30101

## Don't Forget
You can change the ports according to your needs. Don't forget to change the port of JVB from ConfigMap. Change the Jibri config path.
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
