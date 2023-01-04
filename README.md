# 🌐 Geospatial Data Science // Spring 2023 🌐

## Welcome to the exercise sessions for the course in geospatial data science

In this repository you will find the exercises for each session.

**:star2: Please check that you have the latest version of the exercise file before you begin, as we might modify the exercises during the course.**

:question: Use the **[Q&A forum](https://learnit.itu.dk/mod/forum/view.php?id=171258)** on LearnIT for questions.  
:question: We will check it regularly, but invite all course participants to contribute with answers and ideas.

### Getting started

Please use the guide in LearnIT to install the [GDS environment](https://darribas.org/gds_env/). We will use this environment to run the exercises.

### Running the environment

Your weekly workflow to access lecture and exercise notebooks (if you've used the default install with Docker)

1. Save files to *folder of your choice*
    - Files for lectures: Zip folders on LearnIT
    - Files for exercises: This GitHub repository
2. Open a terminal window, navigate to the folder with your files and run `docker run --rm -ti -p 8888:8888 -v ${PWD}:/home/jovyan/work darribas/gds_py:8.0` (see <https://darribas.org/gds_env/guides/docker_install/> for details)
3. Open your browser, go to *localhost:8888*, and insert the token printed on the terminal
4. You are now ready to run the exercise notebooks etc. using the gds_py environment ⭐
