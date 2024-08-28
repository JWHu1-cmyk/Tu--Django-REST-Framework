[Region: us-west1]

==============

Using Nixpacks

==============


context: b9861f2d74dccac752037b05918cfc25

 

╔═════════════ Nixpacks v1.26.0 ════════════╗

║ setup      │ nodejs_18, npm-9_x           ║

║───────────────────────────────────────────║

║ install    │ npm ci                       ║

║───────────────────────────────────────────║

║ build      │ npm install && npm run build ║

║───────────────────────────────────────────║

║ start      │ npx serve -s build           ║

╚═══════════════════════════════════════════╝

 

 

#0 building with "builder-fxRY" instance using docker-container driver

 

#1 [internal] load build definition from Dockerfile

#1 transferring dockerfile: 2.20kB done

#1 DONE 0.0s

 

 

#2 [internal] load metadata for ghcr.io/railwayapp/nixpacks:ubuntu-1722297819

#2 DONE 0.1s

 

 

#3 [stage-0  1/10] FROM ghcr.io/railwayapp/nixpacks:ubuntu-1722297819@sha256:91bbbdf4bf734a471738c36a57b5ba191e5c81ad1d0e9d60d70da2d318639eb8

#3 resolve ghcr.io/railwayapp/nixpacks:ubuntu-1722297819@sha256:91bbbdf4bf734a471738c36a57b5ba191e5c81ad1d0e9d60d70da2d318639eb8 done

 

#3 sha256:3713021b02770a720dea9b54c03d0ed83e03a2ef5dce2898c56a327fee9a8bca 29.53MB / 29.53MB 0.3s done

#3 sha256:d56ae864f638bc715dc7f96e20f795038f08e98266904466c9d2105237aadb65 35.08MB / 35.08MB 0.3s done

#3 sha256:9f035fd1ac8f77604c87839bad174822514bb73ebe3f4450199b25e7715c1ef6 30.16MB / 30.16MB 0.4s done

#3 extracting sha256:3713021b02770a720dea9b54c03d0ed83e03a2ef5dce2898c56a327fee9a8bca 0.7s done

#3 extracting sha256:9f035fd1ac8f77604c87839bad174822514bb73ebe3f4450199b25e7715c1ef6 0.9s done

#3 extracting sha256:d56ae864f638bc715dc7f96e20f795038f08e98266904466c9d2105237aadb65 0.7s done

#3 DONE 2.6s

 

#4 [stage-0  2/10] WORKDIR /app/

#4 DONE 0.1s

 

#5 [internal] load .dockerignore

#5 transferring context: 2B done

#5 DONE 0.0s

 

#6 [internal] load build context

#6 transferring context: 798.47kB 0.0s done

#6 DONE 0.0s

 
