# README

This repo is forked from Render's Flask Hello World and minimal changes were to make FastAPI versin work in render.

This is the [FastAPI](https://fastapi.tiangolo.com//) [quick start](https://fastapi.tiangolo.com/) example for [Render](https://render.com).

## Deployment

Follow the guide at https://render.com/docs/deploy-flask.

Make sure to change the start command in settings tab to this

`gunicorn -k uvicorn.workers.UvicornWorker main:app