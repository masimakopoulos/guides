# Weave, Seneca and Docker buildfiles

If you would like to recreate these images, copy the contents of ../example/micro-services to app, and then build

```bash
docker build -f ./Dockerfile.seneca_webapp -t yourtag_webapp .
docker build -f ./Dockerfile.seneca_offer -t yourtag_offer .
docker build -f ./Dockerfile.seneca_user -t yourtag_user .
```
