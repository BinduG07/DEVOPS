# Exercise 7: Jenkins Setup Using Docker

## Objective

To set up and run Jenkins inside a Docker container and access the Jenkins dashboard through a web browser.

## Technologies Used

- Docker
- Jenkins
- Git and GitHub
- Web Browser

## GitHub Repository

https://github.com/BinduG07/DEVOPS/tree/main/Exercise7

## Project Structure

```text
Exercise7/
├── README.md
├── getting started.png
├── instance configuration.png
├── unlock jenkins.png
└── welcome to jenkins.png
```

## Implementation

1. Pulled the Jenkins Docker image.
2. Created and started a Jenkins container.
3. Configured the required port mappings.
4. Retrieved the initial administrator password.
5. Opened the Jenkins dashboard in a web browser.
6. Completed the initial Jenkins setup.

## Verification Commands

```bash
docker ps
docker exec -it jenkins bash
docker logs jenkins
```

## Result

Jenkins was set up and run inside a Docker container, making the Jenkins dashboard accessible through a web browser.

## Conclusion

This exercise demonstrates how to run Jenkins using Docker and prepare the environment for continuous integration and continuous delivery (CI/CD) tasks.

## Screenshots

The `Screenshots/` folder contains screenshots showing the Jenkins container, setup process, and dashboard.
