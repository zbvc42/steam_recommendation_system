## Steam Recommendation System
=========================

### Executive Summary

The purpose of this project is to build a recommendation system for indie games based their Steam store pages and reviews, accessed through their unofficial API.

The problem with indie games is that there are simply too many of them. Indie developers struggle to make their games stand out, online storefronts struggle deciding which games to showcase, and gamers struggle trying to find games that they'd like. All of these stakeholders would benefit from an improved game recommendation system.

When completed, this project will contain such a recommendation system, trained on publicly available game reviews and store page information from [Steam](https://store.steampowered.com).

### Demo

WIP

### Methodology

- Get data
    - Retrieve list of indie app ids
    - Retrieve Steam store pages for indie games (JSONs)
    - Retrieve reviews for indie games (JSONs)
- Convert JSONs to a more usable database format
- EDA
- Transform data
- Model

### Organization

#### Repository 

* `data` 
    - Directory where data are stored. Empty, since data are not backed up to github. However, notebooks for downloading data are included.

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - Contains notebooks for
        - Data download
        - Data cleaning
        - EDA
        - Modeling

* `docs`
    - contains final report, presentations which summarize the project

* `references`
    - [Steam web API documentation](https://github.com/Revadike/InternalSteamWebAPI/wiki)

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `conda.yml`
    - Conda environment specification

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

#### Dataset

(Links to pickled models will be provided. Links to dataset may not be possible, as Steam may not permit redistributing their data)

### Credits & References

- [Steam web API documentation](https://github.com/Revadike/InternalSteamWebAPI/wiki)