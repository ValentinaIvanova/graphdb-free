## Docker Image for Ontotext GraphDB Free edition

Register on the Ontotext website for the GraphDB free edition. Download the standalone server version and save it in the same folder as the Dockerfile. Build the image and start using !

Note: The version used in the build is 8.0.4-free. Please change the version number in the Dockerfile if required.

#### BUILD THE IMAGE . 
```docker build -t graphdb-free .```

#### TO RUN THE IMAGE . 
```docker run -d -p 7200:7200 graphdb-free```

