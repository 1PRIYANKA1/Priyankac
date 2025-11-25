DevOps Assignment
1. Five DevOps Concepts
1. Continuous Integration (CI)

Developers frequently merge their code changes into a shared repository.
CI tools such as GitHub Actions, Jenkins, and GitLab CI automatically test and validate the changes to prevent conflicts and errors during integration.

2. Continuous Deployment (CD)

After successful integration and testing, CD automatically deploys the updated code to production or staging environments.
This ensures faster, reliable, and repeatable releases.

3. Version Control (Git)

Git helps track modifications in the codebase, enabling collaboration and maintaining a complete history of changes.
Different developers can work independently without interfering with each other’s work.

4. Containerization (Docker)

Docker packages an application along with its dependencies into isolated containers.
This guarantees that the application behaves the same way across different operating systems and environments.

5. Automation

Automation removes manual repetitive tasks involved in building, testing, and deploying applications.
It is essential for CI/CD pipelines, monitoring, provisioning, and overall DevOps efficiency.

2. How I Completed This Assignment (Detailed Explanation)
Docker Commands Used
docker build -t devops-assignment .
docker tag devops-assignment 1priyanka1/devops-assignment:v1
docker push 1priyanka1/devops-assignment:v1

Explanation of Docker Commands

docker build: Builds a Docker image using the Dockerfile from the current directory.

docker tag: Assigns a name and version tag to the built image.

docker push: Uploads the tagged Docker image to my Docker Hub account.

These steps taught me how containers are built and published.

Git Commands Used
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/1PRIYANKA1/Priyankac.git
git push -u origin main

Explanation of Git Commands

git init: Initializes a new Git repository.

git add: Stages all project files for committing.

git commit: Records the changes with a message.

git branch -M main: Renames the branch to main.

git remote add origin: Connects the local repository to GitHub.

git push: Uploads the project to GitHub.

These commands helped me understand how source code versioning and remote repositories work.

3. What I Learned

How to create a Dockerfile and run Linux commands inside a container.
How container images are built, tagged, versioned, and pushed to Docker Hub.
How Git manages code history and collaboration.
How to publish a project to GitHub correctly.
How the DevOps workflow connects Git, Docker, and automation processes.
The importance of reproducible builds and consistent deployment environments.
This assignment gave me practical experience with DevOps fundamentals, Linux basics, Git operations, and Docker usage.
