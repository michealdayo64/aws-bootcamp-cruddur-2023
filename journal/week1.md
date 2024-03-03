# Week 1 — App Containerization

## References

Good Article for Debugging Connection Refused
https://pythonspeed.com/articles/docker-connection-refused/


## VSCode Docker Extension

Docker for VSCode makes it easy to work with Docker

https://code.visualstudio.com/docs/containers/overview

> Gitpod is preinstalled with theis extension

## Containerize Backend

### Run Python

```sh
cd backend-flask
export FRONTEND_URL="*"
export BACKEND_URL="*"
python3 -m flask run --host=0.0.0.0 --port=4567
cd ..
```

- make sure to unlock the port on the port tab
- open the link for 4567 in your browser
- append to the url to `/api/activities/home`
- you should get back json