El proyecto esta divido en 3 repositorios: Grupo2-trabajofinal (Terraform), k8sgrupo2 (cluster kubernete) y app-devops-bootcamp proporcionada para el proyecto.

En el repositorio Grupo2-trabajofinal esta divido en 2 carpetas terraform y CI/CD.
En Terraform la carpeta module cumple con la función de reutilizar el código de terraform de los recursos de AWS que se usaran en los 3 ambientes (dev, prod, staging). También está un archivo dockerinstall para tener preparado a instancia ec2.

En CI/CD está el pipeline de Jenkins, donde se crea una imagen Docker de la app con los recursos necesarios previo a un proceso prueba de seguridad
El repositorio k8sgrupo2 se usa ArgoCD para la gestión de cluster a través de los push de github y kompose ya que brinda todos los archivos necesarios para su funcionamiento.

