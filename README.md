# nodejs-maven-wrapper-template

Template for Node.js project, which doesn't require Node.js or NPM installed. Only requirement is JRE.

## Prerequisites

JRE 8 or higher

## Usage

1. Modify Node.js code under `src/main/resources`
2. Start using Maven:
   - On MacOS / Linux 
   ```
   ./mvnw verify
   ```
   - On Windows
   ```
   mvnw.cmd verify
   ```
   
Without any modifications the code should print `Hello World!`