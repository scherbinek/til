# Setup a virtual environment

It is strongly recommended to use a virtual environment. It can be easily initiiated in the project folders root by the command

```shell
python -m venv env
```

Whereas `env` ist the folder name of the virtual environment which is created.

**Please be aware that the virtual environent is created according to the registered python version, e.g. python might be Python 3.9, or 3.11**

The environment can be activated by the following command

```shell
./env/Scripts/activate
```

Afterwards the command line should indicate by a leading `(env)` that you are in the virtual environment.

The virtual environment can also be activated by chosing the runtime in IDE from its virtual environment folder `env`

Another advantage is creating a current `requirements.txt` by the following command

```shell
(env) pip freeze > requirements.txt
```
