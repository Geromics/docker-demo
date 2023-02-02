
## Checkout
```bash
git clone git@github.com:Geromics/docker-demo.git
git submodule init
git submodule update 
```

## RUN
```bash
docker-compose up -d
```

## Changing branch
```bash
git checkout development 
git submodule update --init --recursive --remote
```
