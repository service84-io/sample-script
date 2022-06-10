# Service84.IO Sample Script

## License
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Usage
This is a sample script that shows off automatic OpenAPI download and client generation for python scripts

This sample script assumes that you have the [SampleService](https://github.com/service84-io/sample-service) running locally and have publish to service definition to you maven local repository

## Build
This is a Python3 project that uses Gradle to generate the python client libraries
used to connect to the services.  The client generation works best with Gradle 6.3.

    gradle processServices
    ./script.py

## Versioning
This project makes a best effort to comply with [SemVer](https://semver.org/)
