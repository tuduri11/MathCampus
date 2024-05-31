# MathCampus

Este repositorio contiene la documentación central de la aplicación web MathCampus,incluyendo enlaces a los repositorios del frontend y backend. 

Autor: Antoni Tuduri Morente.

## Repositorios

- **Frontend**: [https://github.com/tuduri11/tfg-react-tailwind.git](https://github.com/tuduri11/tfg-react-tailwind.git)
- **Backend**: [https://github.com/tuduri11/tfg-backend.git](https://github.com/tuduri11/tfg-backend.git)

## Clonación de Repositorios

Clona ambos repositorios en tu máquina local:
```bash
git clone https://github.com/tuduri11/tfg-react-tailwind.git
git clone https://github.com/tuduri11/tfg-backend.git
```

##Despliegue continuo

**Frontend**

El despliegue continuo del frontend está conigurado usando AWS Amplify. Los detalles de la configuración se encuentran en el panel de AWS Amplify. Cada vez que se realiza un push a la rama 'main', AWS Amplify detecta los cambios y automáticamente construye y despliega la aplicación.

**Backend**

El backend se despliega manualmente en una instancia de EC2. En un futuro se automatizará el despliegue usando scripts.

