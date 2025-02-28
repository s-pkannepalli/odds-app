# odds_app

A new Flutter project.

## Project Structure
Under lib will be all the dart files that hold code for the app. We have structured it using MVVM so that it's more modular. The easiest way to navigate this is that views holds all renderable items, models interacts with the db using repositories (which actually make the network queries), and viewmodels act as an in-between.