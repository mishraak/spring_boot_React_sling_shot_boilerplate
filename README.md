## TODO Use Redux/Flux to make this more useful for large size projects.

# Spring React Template

Often developers choose to have two separate projects (frontend & backend)
and connext them using CORS. This project rather takes the approach of having two 
separate projects but adding frontend as the dependency of backend using build.gradle config.


## Build and Run

Build the app by running:

    ./gradle assemble

Start the app by running:

    java -jar backend/build/libs/backend.jar
