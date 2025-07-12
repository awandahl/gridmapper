# gridmapper

Playing around with code where the meat and inspiration comes from N1KDO and https://github.com/n1kdo/lotw-gridmapper    
I skipped the part of downloading my log from LOTW and am using my local wsjtz_log.adi as source instead.    

- Create a directory for the application
- Put grids.html in the directory
- Make a symlink from wsjtx_log.adi to this directory
- Start up a http server from the same directory like: python3 -m http.server 8000
- Go to http://localhost:8000/grids.html

