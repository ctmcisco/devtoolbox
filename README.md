# PowerShell Alias

PowerShell scripts that enables shorthand for common commands for Docker, Git, and more.

<p align="center">
    <img src="https://user-images.githubusercontent.com/1228996/57589863-f307f680-74ec-11e9-91fd-a9bd07bcbb7c.png"/>
</p>

## Parameters

All aliases accept parameters of the commands they call.  

For example, the below are identical:

```
g cl https://github.com/MichaelJolley/ps-alias.git

git clone https://github.com/MichaelJolley/ps-alias.git
```

## Commands

### Docker

All aliases for Docker begin with `d`.

| Command   | Executes
| ---       | ---
| d c       | docker container ps
| d cs      | docker container start
| d cx      | docker container stop
| d cr      | docker container rm
| d i       | docker image ls
| d it      | docker image tag
| d ir      | docker image rm
| d b       | docker build
| d p       | docker push


### Git

All aliases for Git begin with `g`.

| Command  | Executes
| ---      | ---
| g s      | git status
| g t      | git tag
| g c      | git commit
| g cl     | git clone
| g r      | git reset
| g m      | git merge
| g pl     | git pull
| g ps     | git push



## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!