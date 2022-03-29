# spring-22 Contributing Guide 

This document highlights the various contributing requirements for the automated wiki. This would allow the various automations we have setup to integrate your tutorial into the system. These requirements are built into test cases in a github action which will run when you submit a pull request with your tutorial, to be able to pass all those tests, all the requirements must be satisfied. This is to ensure consistency in our tutorials and allow for quality tutorials. 

## Overall Architecture 

The way the system works is that it treats each tutorial in a markdown file as an individual component that lives and works on its own. This allows markdown files to be pulled and built into a site. 


## Markdown File Requirements

### Comment to Declare Topic 

Each tutorial must have a comment on the first line of the tutorial (befor). The comment should contain a number corresponding to the topics given below:

0 - Kubernetes
1 - Docker

For Example:

```
<!-- 0 -->

```

The comment with the number would tell the system which topic to place the tutorial into. 


### Images

To ensure images are stored reliably and consistently we have decided to store all images related to the tutorial in this repository: 

[Github Images Repository](https://github.com/scalable-web-systems/images)

**Steps to add your image:**

Step 1:

Clone the images repository:

```
git clone https://github.com/scalable-web-systems/images.git
```

Step 2:

Add your image to the folder that corresponds to the semester, at the time of writing this guide and for this example the folder is spring-22. 

Use the following format for the image name:

```
github_username_file_description

Example:

abhinavtripathy_kubernetes_demo

```

![](https://github.com/scalable-web-systems/images/blob/main/admin/adding_images_1.png?raw=true)


### Author Section


### Acknowledgement Section


### Feedback Section 
