#Create a simple Python "Hello, World!" application. 
#The application should be a simple command-line program that prints "Hello, World!" to the console.
#Make sure the Python script is running locally.

 

#Download Docker and write a Dockerfile that can be used to build a Docker image of the application.
#Make sure the Docker image works locally.

 
#Create a GitHub repository (for instance sagi_sony_exce1) to store the application code, Dockerfile, and create README file (MarkDown file).

#Clone your repo to your computer to a different dir, make sure everything works (program runs and docker runs)

 

#Write a GitHub Actions workflow that can be used to run the python app in the action

 

#Write a GitHub Actions workflow that can be used to build and publish the Docker image of the application to ghcr. 
#The workflow should:
#Create a build_and_publish.yml file under .github/workflows.
#Build a Docker image of the application using the Dockerfile.
#Tag the Docker image with the "latest" tag.
#Authenticate with ghcr using a GitHub Personal Access Token (PAT).
#Publish the Docker image to ghcr.
#(Bonus) Create a version control for the Docker image in ghcr, by tagging it with a version number. For example, "v1.0.0".
#Push the code and Dockerfile to the GitHub repository.
#Run the GitHub Actions workflow to build and publish the Docker image to ghcr.
#Create a README file that explains how to build and run the application locally, how to run the GitHub Actions workflow, and how to pull the Docker image from #ghcr
