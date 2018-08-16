# dockdx

Assuming this Dockerfile is built something like this: 

```
docker build -t dockdx .
```

In a DNAnexus job, run:

```
docker run -it -v $PWD:/tmpdx /bin/bash
```

In this interactive terminal, type:

```
source /tmpdx/environment
dx ls
python
# import dxpy ...
```