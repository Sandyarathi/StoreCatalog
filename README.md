# StoreCatalog
##SnapShare : Photo sharing Application
```
A data driven Web Application that displays photos shared by 
different users allows authenticated users to manage the photos.
```
```
Initial steps:
-------------
  Install Vagrant and VirtualBox
  Launch the Vagrant VM using the following steps
    $vagrant up
    $vagrant ssh
    $cd /vagrant
    $cd SnapShare
    
Database Setup:
---------------
  Remove existing .db file if any using command: $rm PhotoCollections.db
  $python Albumsdatabase_setup.py
  $python fakedata.py
  
Run Application:
----------------
  python project.py
  
  
Note: Web server is configured to run on http://localhost:8000/
```
