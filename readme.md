## Instale WordPress y Mysql en el Clúster de Kubernetes con volúmenes persistentes
<img src="https://speckyboy.com/wp-content/uploads/2012/10/mysql_wordpress_hero.jpg">

#### Pasos

1. Clone el repositorio
`https://github.com/JhonnyVeraCervantes/Wordpress-Kubernetes.git .`

2. Ejecute el siguiente comando para iniciar un clúster con wordpress y mysql

`kubectl apply -f ./`

3. Cambie la contraseña en kustomization.yaml 

4. Chequee usando estos comandos

```
kubectl get pods
kubectl get services
kubectl get pvc
kubectl get secret
```

## Para Eliminar
1. To delete the cluster run `kubectl delete -f ./`

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


## Expresiones de Gratitud 🎁

* ¡Dale un ⭐️ si este proyecto te ayudó!
* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
