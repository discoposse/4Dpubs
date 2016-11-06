<!--
http://www.apache.org/licenses/LICENSE-2.0.txt


Copyright 2015 Turbonomic

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# **4Dpubs** <sup><sub>_The 4D refers to Distributed Dynamic Document Display._</sub></sup>

----

1. [Overview](#overview)
2. [Getting Started](#getting-started)
  * [System Requirements](#system-requirements)
  * [Building with Docker - EXPERIMENTAL](#building-with-docker)
3. [Sites using 4D](#sites-using-4dpubs)

## Getting Started

### System Requirements

Any web server can serve up the files.  Simply copy the contents html folder to the root folder of a web server of your choice.  

### Building with Docker

A basic Docker Compose file is included under the Docker folder.  Testing with Docker is still experimental as we develop more deployment methods to run 4Dpubs.

## Sites Using 4Dpubs

Single-source is one advantage of 4Dpubs. Because the source is DITA, you can publish 
that source in any other format that DITA supports. The 4D content displays dynamically 
in the app, and you can generate static publications for viewing outside of the app.
Turbonomic uses 4Dpubs to dynamically deliver help and API documentation. To see this 
in action, install the Turbonomic product. You also can see static versions 
of this documentation:
#### https://docs.turbonomic.com

Two examples of 4Dpubs in action:

Outline of Science -- http://cudspan.net/4D_2_Git/4Dpubs/science_index.html

4Dpubs Introduction -- http://cudspan.net/4D_2_Git/4Dpubs/index.html



