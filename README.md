# readme

This repo contains standards and structure for geosysanalysis organization  

## organization archetype

This section talks about the basic structure of the `GoeSysAnalysis` Github Organization, based off [this gist column](https://gist.github.com/rwnfoo/3e19747f6dc2c5b9cfb0ff9c89d834b4)

* `Organization` represents the collectino of teams and repositories
* `Project Teams` separate projects and project families
* `Development Teams` separate user access and development
* `Repos` are respositories of code that do one thing

![](https://user-images.githubusercontent.com/865381/37910942-c2c8c012-30dc-11e8-910b-1bda5b22fb25.png)

```
                        ________________            ________________    
                        |  Proj Team 1 |            |  Proj Team 2 |
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

This section talks about the Project Teams in the `GoeSysAnalysis` GitHub Organization (updated 03022023)
* [Hydrus](https://github.com/orgs/geosysanalysis/teams/hydrus)
* [MSCP](https://github.com/orgs/geosysanalysis/teams/mscp)
* [rivereyes](https://github.com/orgs/geosysanalysis/teams/rivereyes)

