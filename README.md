## The project shows a basic configuration how to run a job workflow in a Docker container

### Overview 
Service containers are Docker containers that provide a simple and portable way for you to host services that you might need to test or operate your application in a workflow. 
For example, your workflow might need to run integration tests that require access to a database and memory cache.

### Getting Started
- Node.js and npm must be installed on your system.
- You can clone the repo and run `npm install`

### Docker Containers & GitHub Actions
What does the Docker Container do ? 
- Packeges the code plus its execution environment.
### Why use Container ?
- Full control over environtment and installed software
- Great for creating re-usable execution packages
### Why use Containers for Jobs ?
- You can run Jobs in pre-defined environments
- Great for Jobs that need extra tools or lots of customization
### Why use Service Containers ?
- Extra services can be used by Steps in Jobs
- Locally running, isolated testing database
