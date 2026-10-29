# 🌱 GreenCI: Carbon-Aware DevOps Platform

## About the Project

GreenCI is a carbon-aware DevOps platform designed to estimate the carbon emissions of CI/CD builds and recommend sustainable build scheduling decisions.

The platform considers carbon intensity, estimated energy consumption, build urgency, and whether a build can safely wait.

## Objectives

* Estimate carbon emissions associated with CI/CD builds.
* Recommend whether a build should run, be delayed, or be skipped.
* Record build evaluations in a database.
* Display build history and sustainability metrics through a dashboard.
* Receive GitHub push events using webhooks.

## Technologies Used

* Python
* FastAPI
* Streamlit
* SQLite
* GitHub Webhooks
* Uvicorn

## Main Features

* Build evaluation API
* Carbon emissions estimation
* Carbon-aware scheduling recommendations
* Build history persistence
* Sustainability impact dashboard
* GitHub push event integration

## Important Note

Carbon emissions are estimates based on the supplied energy consumption and carbon intensity. Illustrative sample values are not live grid measurements.

## Project Status

Under development.
