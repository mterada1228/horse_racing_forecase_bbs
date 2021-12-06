# Setup
Clone a this repository.

``` sh
$ git clone git@github.com:mterada1228/horse_racing_forecase_bbs.git
```

## Install `direnv`
`direnv` is necessary for this project. Run the following commands, and Install the `direnv`.

``` sh
$ brew install direnv

$ echo 'eval "$(direnv hook zsh)"' >> ~/.zshrc
$ source ~/.zshrc

$ cd horse_racing_forecast_bbs
$ direnv allow
```

## Clone application repositories
Move to the following directory.

``` sh
$ cd horse_racing_forecase_bbs
```

- Front end
  ``` sh
  $ git clone git@github.com:mterada1228/horse_racing_forecast_bbs_front_end.git
  ```

- API
  ``` sh
  $ git clone git@github.com:mterada1228/horse_racing_forecast_bbs_api.git
  ```

# Construct development environment
Run the following commands to construct containers for services.

``` sh
$ docker-compose up -d
```

Open http://localhost:3000 with your browser to see the result.
