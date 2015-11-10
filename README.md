# node-webkit-NW.js--PhotoEditor
Its Desktop application. User can select images and can edit them.





# Development Environment Setup

 Pre-requisites:
 -  Node.js

Install  **NodeJS** x64 distributions from its websites.

To install Node-webkit:

```bash
npm install -g nw
```

To install Node-webkit-builder:

```bash
npm install -g nw-builder
```



# Runing Application.

Move to the Project Directory

```bash
$cd project Directory
```

-Install project dependence:

```bash
npm install
```



- Create application.

```bash
$ nwbuild -p win32,win64,osx32,osx64,linux32,linux64 lens
```

#Tutorial Followed
![Creating a Photo Discovery App with NW.js Part 1]( https://scotch.io/tutorials/creating-a-photo-discovery-app-with-nw-js-part-1)
![Creating a Photo Discovery App with NW.js Part 2]( https://scotch.io/tutorials/creating-a-photo-discovery-app-with-nw-js-part-2)




#License
MIT