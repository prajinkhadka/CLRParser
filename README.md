# CLRParser

**This project demonstrates the working of Simple CLR parser in Compiler**

1. Take input productions. 
2. Compute CLR1 Table.
3. Take input the string to be matched.
4. Parse and present the parse table.

Live Demo : [CLR Parser Live Demo](http://20.97.217.77:8501/)


### Running project locallly


For building the project locally, 

1. Install [Docker](https://www.docker.com/)
2. Clone the repo 
   ```https://github.com/prajinkhadka/CLRParser.git```
4. Navigate to the Project Directory.
   ``` cd home/prajin/ProjectDirectory ```
3. Build the Docker Image 
  ``` docker build -t CLR_demo:v1 .  ```
4. Run the docker image in the container 
   ``` docker run -p 8501:8501 CLR_demo:v1 ```
5. Headover to ```localhost:8501/```




