# code-server

## Use docker
```
mkdir -p $HOME/coder/workspace
docker run \
  --name code-server \
  --rm \
  -p 3000:3000 \
  -e PASSWORD=password  \
  -e PORT=3000 \
  -v $HOME/Workspace/code-server \
  codercom/code-server:latest
```

## Deploy Azure Container Apps


