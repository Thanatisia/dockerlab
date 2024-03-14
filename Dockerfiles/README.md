# Place all your Dockerfile submodules here

## Information
### Project Filesystem structure
- [service|image-name]/
    - README.md
    - authors/
        - [author-name]/
            + [git-submodule-here] : Please add the git submodule in this directory

## Instructions
1. Please update [Entries](#entries) whenever you add a new image/service in the following format
    - [image|service-name] : Description of project/package
        - authors
            + author-name : Submodule package's remote repository server URL

2. Add the git submodule
    ```bash 
    git submodule add https://github.com/author/project
    ```

## Usage
- Clone this repository
    ```bash
    git clone https://github.com/Thanatisia/dockerlab
    ```

- Change directory into local repository
    ```bash
    cd dockerlab
    ```

- Initialize and clone all submodule package repositories
    ```bash
    git submodule update --init
    ```


## Entries


## Wiki

## Resources

## References

## Remarks

