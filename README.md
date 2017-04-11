A project to explore applying machine learning on blood glucose data

Setting up project:
- make sure docker is running
- navigate to root directory of project
- add notebooks folder to root directory
- fill in secrets for mongo-to-csv
- download data from nightscout to csv using command
- run:
docker run --rm -it -p 8888:8888 -v "$(pwd)/notebooks:/home/jovyan/work" jupyter/tensorflow-notebook
