LAB-6
  1. Review Simulated CI/CD Pipeline Configuration:
    Build Stage:
    Code Commit: Developers commit code to a version control system, triggering the CI pipeline.
    Docker Image Creation: Dockerfiles define the environment and dependencies, and Docker builds an image which encapsulates the application and its runtime.
    Test Stage:
    Automated Testing: Docker images are used to spin up containers where automated tests are conducted, ensuring that the application behaves as expected in an environment identical to production.
    Deployment Stage:
    Container Registry: Successfully tested Docker images are tagged and pushed to a Docker registry.
    Orchestration and Deployment: Tools like Kubernetes or Docker Swarm manage the deployment of these images into containers across different environments, handling scaling and load balancing.
  2. Analyze Enhancements and Potential Issues:

   Enhancements: Consider how Docker’s containerization benefits the build, test, and deployment processes by providing consistency, portability, and scalability.
          
    utiliza menos recursos porque no utilizamos un sistema operativo completamente nuevo montado en cada aplicación, se pueden crear Múltiples pods en el mismo entorno para obtener la escalabilidad que necesitamos.
  
   Potential Issues: Reflect on any possible challenges that might arise with Docker integration, such as security vulnerabilities in images, complexity in managing 
      large numbers of services, or difficulties in orchestrating containers.

      la desventaja que le veo es que permite todo tipo de tráfico lo cual lleva al tema que si no existe una confugiracion adecuada o en otro ejemplo si no hay configuración, podemos filtrar datos de mucho valor.

  3. Write an Analysis Report:

         Existe como todo ventajas y deseventajas de las cuales yo considero como ventaja el proceso de sus herramientas  ya que en cada modificacion de codigo  tengan que pasar por el proceso del pipeline, desde Secutiry Scans hasta Code Quality. como desventaja seria la si llegas a configurar mal los datos son vulnerables.
   
