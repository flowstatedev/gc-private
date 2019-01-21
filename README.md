# gc-private
Change Garmin Connect privacy settings for multiple activities (based on date range)

```
usage: gcprivate.py [-h] [--version] [--username [USERNAME]]
                    [--password [PASSWORD]] [--startdate [STARTDATE]]
                    [--enddate [ENDDATE]] [--privacy [PRIVACY]]

optional arguments:  
  -h, --help            show this help message and exit    
  --version             print version and exit  
  --username [USERNAME]  
                        your Garmin Connect username (otherwise, you will be
                        prompted)  
  --password [PASSWORD]  
                        your Garmin Connect password (otherwise, you will be
                        prompted)  
  --startdate [STARTDATE]  
                        the date of the first activity to set to private (e.g.
                        2018-09-30) (otherwise, you will be prompted)  
  --enddate [ENDDATE]   the date of the last activity to set to private (e.g.
                        2018-10-30) (otherwise, you will be prompted)  
  --privacy [PRIVACY]   public, private, subscribers, groups  
  ```
