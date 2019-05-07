You will need to implement internal website API, which supports following:
* /job. Depending on a POST params it should:
  * Give a new job
  * Give details about job
  * Update job status
* /printer. Depending on a POST params it should:  
  * Refresh printer healthcheck
  * Reschedule jobs

Every API call must send Username (app) and Password (token) as POST params

I am providing code in the repository to you under an open source license. Because this is my personal repository, the license you receive to my code is from me and not my employer (Facebook)