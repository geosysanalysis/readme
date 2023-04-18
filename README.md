# readme

This repo contains standards and structure for geosysanalysis organization  

## What is Github?

* Github has [some fantastic documentation about what it is](https://docs.github.com/en/get-started/quickstart/hello-world). 
* On Github [clone, add, commit, push, pull](https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/)

In short: Github is a code hosting platform that makes it easier to version control, share, and document code for yourself and for others. 

The most elemental unit of github is a repository (or `repo`), which is a collection of files -- files, images, videos, spreadsheets, and data sets -- that are about a single product. 

Other features of GitHub, such as `projects` and `teams` make it easier for you to prioritize work in a `repo` and share it with others. 

For GSA, the goal is to create a way to share and document new and existing projects so: 
* 
* 
* 

## organization archetype

This section talks about the basic structure of the `GoeSysAnalysis` Github Organization, based off [this gist column](https://gist.github.com/rwnfoo/3e19747f6dc2c5b9cfb0ff9c89d834b4)

* `Organization` represents the collectino of teams and repositories
* `Product Teams` separate products and product families
* `Development Teams` separate user access and development
* `Repos` are respositories of code that do one thing, usually a project within a product

![](https://user-images.githubusercontent.com/865381/37910942-c2c8c012-30dc-11e8-910b-1bda5b22fb25.png)

```
                        ________________            ________________    
                        |  Prod Team 1 |            |  Prod Team 2 |
                        |    ______    |            |    ______    |
                        |   |      |\  |            |   |      |   |
            Dev Team A--|   | Repo | \ |            |   | Repo |   |------Dev Team A
                        |   |______|  \|            |   |______|   |
                        |              |            |              |
                        |    ______    |\           |    ______    |
                        |   |      |   | \          |   |      |   |
                        |   | Repo |---|--Dev Team C|   | Repo |---|--Dev Team D
                        |   |______|   | /          |   |______|   | /
                        |              |/           |              |/
                        |    ______    |            |    ______    |
                        |   |      |  /|            |   |      |  /|
            Dev Team B--|   | Repo | / |            |   | Repo | / |
                        |   |______|/  |            |   |______|/  |
                        |              |            |              |
                        |______________|            |______________|
```

            
## Organization Details 

This section talks about the Project Teams in the `GoeSysAnalysis` GitHub Organization
* [Hydrus](https://github.com/orgs/geosysanalysis/teams/Project-hydrus)
* [MSCP](https://github.com/orgs/geosysanalysis/teams/Project-mscp)
* [rivereyes](https://github.com/orgs/geosysanalysis/teams/Project-rivereyes)
* [Bisbee](https://github.com/orgs/geosysanalysis/teams/project-bisbee)

