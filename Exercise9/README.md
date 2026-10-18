# Exercise 9: Jenkins Multi-Stage Pipeline

## Objective

To automate the build, testing, deployment, and application testing of a Python Flask application using a Jenkins Declarative Pipeline.

## Technologies Used

- Jenkins
- Docker
- Python
- Flask
- Git and GitHub

## GitHub Repository

https://github.com/BinduG07/DEVOPS/tree/main/Exercise9

## Project Structure

```text
Exercise9/
├── python-flask-app/
│   ├── app.py
│   ├── requirements.txt
│   ├── test_app.py
│   └── Jenkinsfile
├── Screenshots/
│   ├── create files.png
│   ├── jenkins pipeline.png
│   ├── push folder to git.png
│   └── push jenkinsfile.png
└── README.md
```

## Pipeline Stages

1. **Build:** Install the required Python dependencies.
2. **Test:** Execute unit tests to verify application functionality.
3. **Deploy:** Copy the application files to the deployment directory.
4. **Run Application:** Start the Python Flask application.
5. **Test Application:** Verify that the running application responds correctly.

## Execution Steps

1. Created a Python Flask application.
2. Added the required dependencies and unit tests.
3. Created a `Jenkinsfile` containing the pipeline stages.
4. Uploaded the project files to GitHub.
5. Configured a Jenkins Pipeline job to retrieve the `Jenkinsfile` from GitHub.
6. Executed the pipeline and verified the stages using the Jenkins console output.

## Result

The Jenkins multi-stage pipeline was configured to automate the build, testing, deployment, and application testing of the Flask application.

## Conclusion

This exercise demonstrates how Jenkins Declarative Pipelines automate the build and testing process and run a Python Flask application through multiple pipeline stages.
