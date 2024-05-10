# Incite



## Buidling and running docker image
- [Streamlit Tutorial](https://docs.streamlit.io/deploy/tutorials/docker)

### Build Dockeer Image
```chatinput
docker build -t incite .
```
### Check the Docker Image Built
```chatinput
docker images
```
### Run the Docker Container
``` 
docker run -p 8501:8501 incite
```