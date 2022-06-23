# AZ-900-Virtual-Machine
Guía para crear un recurso en el portal de Azure y configurar una máquina virtual.

En el menú hacemos clic en "Todos los servicios"
![VM2](https://user-images.githubusercontent.com/106035353/174952710-c4ca367f-9229-4406-8ccb-ac1ad4796221.png)

Hacemos clic en "Compute" y posteriormente en Máquina Virtual de Azure
![image](https://user-images.githubusercontent.com/106035353/174952842-46ef4a3a-dc14-46f9-be68-31b408a08486.png)

Damos clic en "Crear Máquina Virtual de Azure"
![VM4](https://user-images.githubusercontent.com/106035353/175203235-e703ac55-8bb4-4af5-ba0e-a27041445a7c.png)

Llenamos los campos, eligiendo la imagen o el SO que se desea así como la tarifa a pagar:
![VM5](https://user-images.githubusercontent.com/106035353/175203438-5e16a940-a73b-4a26-8255-241661815fc9.png)

![VM6](https://user-images.githubusercontent.com/106035353/175203447-2a6add3a-e354-48f4-b49a-318f275be917.png)

Hacemos clic hasta llegar a Etiquetas y asginamos si así lo requiere:
![VM8](https://user-images.githubusercontent.com/106035353/175204841-0c31e5e2-1d9e-4089-94ad-bda4cf0c650e.png)


Hacemos clic en Revisar y Crear, esperamos a que la implementación se implemente:
![VM9](https://user-images.githubusercontent.com/106035353/175204891-f540f5a3-e0e3-42d6-93ca-c223bd334312.png)
![VM10](https://user-images.githubusercontent.com/106035353/175204906-77a1aec7-cff0-4e74-a544-34c16b03be64.png)

Una vez implementado, hacemos clic en "Ir al recurso":
![VM20](https://user-images.githubusercontent.com/106035353/175204990-659b4fcb-060c-4a47-9f21-38c302c4d3f8.png)


Hacemos clic en Conectar y (en este ejemplo) elegimos RDP:

![VM11](https://user-images.githubusercontent.com/106035353/175205168-5f3bcfc7-b04e-455c-a1be-6d9b7dd9b619.png)

Hacemos clic en "Descargar archivo RDP" y lo ejecutamos:
![VM12](https://user-images.githubusercontent.com/106035353/175205204-e33e9e25-7a63-4e8c-9ad5-2f017a617bd8.png)

En la ventana de credenciales hacemos clic "Más opciones" e ingresamos las claves previamente configuradas (usuario y password):
![VM13](https://user-images.githubusercontent.com/106035353/175205315-fb788d1c-be2e-494a-a184-80c83cd107e7.png)
![VM14](https://user-images.githubusercontent.com/106035353/175205322-15ca5dfb-5b55-43aa-987c-693f8910ec91.png)

Aceptamos la conexión:
![VM15](https://user-images.githubusercontent.com/106035353/175205471-a265d215-3149-4725-86ca-4bbd41f8a5da.png)


Se abrirá la ventana completa con la máquina virtual lista para usarse, entramos a internet, etc.
![VM16](https://user-images.githubusercontent.com/106035353/175205510-56a89760-d930-4990-963b-2c041114de36.png)
![VM17](https://user-images.githubusercontent.com/106035353/175205522-20d82262-4ae0-4f88-bae0-e87b6805742b.png)

Para eliminar la Máquina Virtual, en el portal de azure, nos vamos al menú y hacemos clic en "Grupo de Recursos"
![image](https://user-images.githubusercontent.com/106035353/175205771-01520a7f-bea9-4a3b-a7d1-dd4816332913.png)

Hacemos clic en el recurso (lab01-dr) y hacemos clic en Eliminar grupo de recursos:
![VM18](https://user-images.githubusercontent.com/106035353/175205897-b143dd09-9cd9-4a24-b2f5-065ed1ea1208.png)

