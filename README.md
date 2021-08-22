# Welcome to Polyu Virtual Lab!

## Major Features

* Starting Lab Sessions
  * Provides an isolated Linux-based environment for completing hands-on lab exercises
  * Max. 4 hours per session
    * The running processes will be killed when the session is terminated/expired
  * Each user can have at most 2 running lab sessions \(excluding the filebrowser  app\)
    * Users should first terminate the existing session before starting new lab session\(s\)
  * Defined resource quota for each lab session 
    * Ram, vCPU, ephemeral storage consumed
    * The processes/lab session may be terminated to free up resources if the defined quota limit is reached 
* Control Panel
  * Show the running apps
  * Terminate the running apps
* The lab environment provides 2GB of persistent volume per user for storing data \(e.g. the workspace folder\)

## Notes

* Only selected folders \(e.g. ~/workspace\)  will be retained a persistent storage
  * Changes made/Files stored in other folders are not persistent and will be lost after the session is expired/terminated.
* When the lab session is terminated/expired, all running processes will be terminated
  * You may need to restart when you start the lab session again.

