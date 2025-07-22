# Image Search using Milvus Vector Database
## To start milvus docker service
* This service is used if want to host a localhost uri or else just local (Currently using on local storage)

* If using local storage no need to run the docker service for milvus

## For windows, run (or using Docker Desktop)
```
To start,
standalone.bat start

To stop,
standalone.bat stop
```

## For wsl/ubuntu, 
```
To start, run
docker compose up -d

To stop, run
docker compose down
```

## Code
* Currently milvus does not support for Windows, Use WSL instead
* Run the codeline at milvus_search.ipynb, put the dataset locally  

## Result
The query for both image and text should be working fine. The accuracy is depends on the total dataset embedded
