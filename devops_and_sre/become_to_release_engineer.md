# Release Engineer
Building and delivering software!!

#### Intro Philosophy
Release engineers and SREs work together to develop strategies for canarying changes, 
pushing out new releases without interrupting services, and rolling back features that demostrate problems.

## TLDR Concepts

### Self Service Model
IN ORDER TO SCALE, Teams must be self-sufficient.
All the product releases should be automated using the necessary tools.
Build and deployment tools are truly automatic and only require
involvement if and when problems arise.


### High Velocity
Small changes per version!.
Releases quickly and frequently.
Artifacts are tested and best version of new build is deployed to prod! :
We have test results to make the best decision which and when release. 


### Hermetic Builds
We expect identical results with same Inputs.
The Artifact: the build of the product are only dependent on the known
version of compilers, dependencies, etc.
and INSENSITIVE with other libraries and bin in the build machine.
The build process is self-contained and must not rely on services that are
external to the build env.

### Enforcement of Policies and Procedures
Who can do this operation ? Which resources will be impacted ? 
We track all the operations, with security and access control.
We have reports with all the changes in the release that is archived with the artifacts.
Those reports are super useful for troubleshooting.
 

### Others

* Identifiability: Identify all the necessary tools, envs, Artifacts + all things requried for a product release.
* Reproducibility: Able to integrate sources, data, third-party and deployment externals of sw.
* Consistency: Have stable framework to be consistent.
* Agility: Implement the best engineering practices in the sw cycle's productivity.


#### Core 

## Blogs


What is Release Engineering and why is it important ?
<br>
https://www.chubbydeveloper.com/release-engineering/


## Books

https://sre.google/sre-book/release-engineering/

