# JobPortal

## Language and Framwork 

```bash
 Java , SpringBoot , JPA , H2 database
```

## Data Flow

 1. Controller (JobController.java)

```bash
 #Apis with CRUD repo

  getAllJobs()
  getJobByid
  addJob()
  
 #Apis with Custom Finder

  getJobsByTitle()
  getJobsByDesc()
  getJobsBylocation()
 
# Apis with Custom Query

  DeleteJobs()
  UpdateJob()

```
2. Service (JobSerice.java)

```bash
 #Service with CRUD repo

  getAllJobs()
  getJobByid
  addJob()
  
 #Service with Custom Finder

  getJobsByTitle()
  getJobsByDesc()
  getJobsBylocation()
 
# Servicewith Custom Query 

  DeleteJobs()
  UpdateJob()
```

3. Model ( job.java , JobType.java )

```bash
  Students()
  Department()
  Event()
```
4. Repository ( IJobRepo.java)

```bash
  IJobRepo()
  getJobsByTitle()
  getJobsByDesc()
  getJobsBylocation()
  deleteJob()
  updateJobSalary()
```

## Data Structure Used

```bash
  H2 as database
```

## Project Summary

Job Search Portalis a system to handle activities related to Jobs details and services here u can add,get,update or delete a job also we used H2 as our Database
 
  #### Features for Job Search Portal

- you can Add/Create Jobs.
- you can Get all jobs details.
- you can Get all Job details by Job id.
- you can Get all Job details by Title,Description,Location.
- you can Update specific Job details/Salary by using Job id.
- you can Delete/Remove a Job details/Contact by Job id.


  
## Author

- [@Ankita]


## License

[MIT](https://choosealicense.com/licenses/mit/)

