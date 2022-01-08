# Problem statement
This project is designed to create an ML platform to automate the entire process. This begins
from data retrieval from either of the 3 cloud platforms like AWS, Azure and GCP.
We can create custom projects to schedule the data consumption. Therefore the files
accessed are directly from the cloud with
little or no manual processes involved. We have designed it in such a way that when a project
is created for a requirement we can schedule jobs for training
at specific time frames by providing the necessary inputs The incoming data from the client is
put through validation techniques like file name validation,
data validation (column name,file format,number of missing columns) and the individual is
notified via mail when there is noticeable event that occurs.


# PythonCloudLibrary
CloudLibrary


## To create conda environment

```
conda create -n env_name python==3.7
```


## configure your conda environment in pycharm

```buildoutcfg
conda activate env_name
```


## Install requirements.txt
```buildoutcfg
pip install -r requirements.txt
```


### to create requirements.txt
```buildoutcfg
pip freeze>requirements.txt
```

```
python project_library_layer\initializer\setup_configuration.py
```
![image](https://user-images.githubusercontent.com/52704446/148636634-f0bd537b-b86d-4db3-99c7-736bb8c4ce2e.png)
