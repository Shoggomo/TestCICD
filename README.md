## Development Setup

 1. Make sure, that Java (>= version 11) is installed and set up correctly (check with `javac -version` command)
    - If another version was installed previously and the environment variable is corrected, you may need to restart
 2. Setup git hooks by executing the `setup_githooks` scripts in `tools`


## Git Hooks

On every commit git automatically runs codestyle before committing.

## CI/CD Pipeline

On every push and merge the pipeline runs codestyle, all tests and checks if the code builds.
If a version tag (e.g. v1) was added, it will be released on the github project.
