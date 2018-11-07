# ModelChimp: Scikit Example

This repository contains example code of using ModelChimp with Scikit Framework



## ModelChimp Installation


```shell
pip3 install modelchimp
```

Its assumed that scikit is already installed


## Define the project

Create the project in modelchimp and copy the project key to the code in main.py

![alt text](https://docs.modelchimp.com/doc_project_definition.png )
![alt text](https://docs.modelchimp.com/doc_project_key.png )

```python
# MODELCHIMP: import and instantiate modelchimp tracker
from modelchimp import Tracker
tracker = Tracker('<PROJECT KEY>', 'localhost:8000', auto_log=True)
```

## Execute the code
Execute the code with the following command

```bash
python3 main.py
```