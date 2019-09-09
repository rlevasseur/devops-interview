# DevOps Interview Exercises

This repo contains sample java application set up in the standard maven directory structure.

1. Upgrade the gradle wrapper to version 4.10.2 with the 'all' distribution
   https://docs.gradle.org/current/userguide/gradle_wrapper.html
2. Configure gradle multi-project so the app module compiles, with core as a dependent project
3. Make sure unit tests compile and run in core project
4. Use the application plugin in the app project to create an application distribution
   https://docs.gradle.org/current/userguide/application_plugin.html
5. In app build, add the app/LICENSE file into the application distribution

