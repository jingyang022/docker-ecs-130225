## Lesson 3.4 Class Activity 1: Publishing a image to AWS ECR

<p>Step 1: Create a private ECR repository
<br>Step 2: Build and Push your image into your ECR repository
<br>Step 3: Verify that your image has been pushed

--------------------------------------------------------------
## Lesson 3.4 Assignment: Integrate Github workflow

- Besides using just the latest tag, make use of the Github Context: github.sha to tag your images. So that every image in your ECR repository would have a unique tag.
- Set up a Github workflow such as any pushes to the main branch, will trigger a workflow to build and push your image to your ECR registry.
- Submit your github repository with your workflow.
