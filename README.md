# Sommeliers
##### UnOfficial Repo

## Overview
Sommeliers is an Apache Syncope-based solution that aims to manage user memberships within groups based on their individual attitude to be "sommelier" about a particular topic.

## Features
- Apache Syncope integration
- Meticulous group assignment
- We also have Staffelli!
- Yet, sadly, we still have Albert...

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/acarullo/sommeliers.git
2. Build the project:
   ```sh
   cd sommeliers && mvn clean install
3. Run the project in embedded mode:
   ```sh
   cd fit && mvn -Pembedded
## Development

Want to contribute? Great!
If you have any membership to assign feel free to submit your own PR
Consider adding your Group, if it's not listed, and then create your membership based on User and Group on `core/src/test/resources/domains/MasterContent.xml`.
