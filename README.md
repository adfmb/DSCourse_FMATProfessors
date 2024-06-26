# DSCourse_FMATProfessors

## Objective
- To share the basics of some tools (mainly from *python*) that could be helpful for reading, manipulating, cleaning, transforming and preparing data prior the training-a-model-step.

- From there, teach how to deploy a model to a possible-productive-environment to be consumed for other users through *Google Cloud Platform*

## Day 1:
### Discuss & Setup our Work Environment Options

#### For This Course:
  - Local (Linux's Kernel 🙏)
  - [Github](https://github.com/adfmb/DSCourse_FMATProfessors/tree/jalfmb01)
  - [Conda](https://www.anaconda.com/download) 🐍
  - [Google Cloud Plataform](https://cloud.google.com/) ☁️
  - [Google Colab](https://colab.research.google.com/#create=true) ☁️
  - [Kaggle](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset) ☁️
  - [R](https://cran.itam.mx/) & [RStudio](https://www.rstudio.com/products/rstudio/download/#download)    (**maybe*...)
  #### & For Life:
  - [Visual Studio Code](https://code.visualstudio.com/download)
  - [Vertex AI Studio](https://cloud.google.com/vertex-ai-notebooks?hl=es_419) (**$$$**) ☁️
  - AWS Sagemaker (**$$$**) ☁️
  - [Docker 🐳](https://www.docker.com/products/docker-desktop/) (Linux's Kernel! 🙏🙏)
 
### Working from Terminal:

> (*) For this course,
> 
> - If Windows:
>
>   - You can try this from Anaconda Powershell Prompt:
>
> - else:
>   - Use your own *kernel-linux-shell*

#### Linux Basic Commands


- **`cd`**: Change directory.
    - Example: **`cd ~/Documents/Data`**
- **`pwd`**: Print working directory (displays the current directory).
- **`ls`**: List files and directories in the current directory.
    - Example: **`ls -l`** (long format)
- **`mkdir`**: Create a new directory.
    - Example: **`mkdir NewFolder`**
- **`touch`**: Create an empty file.
    - Example: **`touch data.txt`**
- **`cp`**: Copy files and directories.
    - Example: **`cp source_file destination_directory`**
- **`mv`**: Move or rename files and directories.
    - Example: **`mv old_file new_name`**
- **`rm`**: Remove files and directories.
    - Example: **`rm file.txt`**
- **`cat`**: Concatenate and display file content.
    - Example: **`cat file.txt`**
- **`echo`**: Repeats everything you handles it to repeat
    - Example: **`echo Hola Mundo!`**
- **`grep`**: Search for patterns in files.
    - Example: **`grep "pattern" file.txt`**
    
- `|`: **pipe** to concatenate the output of prev command as the input of the next one.
    - Example: **`history | grep git`**
    
- **`find`**: Search for files and directories in the filesystem.
    - Example: **`find /path/to/search -name "file_name"`**
- **`>[file_name]`** :  Sends the output —usually showed in the prompt— to the filename file, creating the last one if it does not exist
    - Example: **`history | grep git > analysis.txt`**
    - if **`>>`** is used, then the output will be appended to the file if it already exists, otherwise, it will be created


### Git / Github

- `git clone`  Clone/download 
- `git checkout` Move across branches
    - `-b` Causes a new branch to be created
- `git status` Show the working tree status
- `git add` Add file contents to the index
- `git commit` Record changes to the repository
    - `-m` Use the given *text* as the commit *message*
- `git push` Update remote refs along with associated objects

  > cd `<YOUR_WORKING_DIRECTORY_PATH>`
  >

  > git clone https://github.com/adfmb/DSCourse_FMATProfessors.git
  >

  > cd `DSCourse_FMATProfessors`
  >

  > git checkout -b `<YOUR-USERNAME>`
  >

  ### Setting up our Virtual Env
  - Install [Conda](https://www.anaconda.com/download) 🐍 and then execute from Shell:

  > conda create --name dscourse_fmat python==3.7  -y -v
  >
  

  > conda activate dscourse_fmat
  > 
   
  > pip install -r requirements.txt


  ### Examples for manipulating data from terminal and bash files
 
## Day 2:


 
## Day 3:


## Day 4:


## Day 5:



 

