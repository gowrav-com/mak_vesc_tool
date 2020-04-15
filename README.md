Create Git Personal access tokens for Releases https://github.com/settings/tokens
Use Travis encrypted environment variables https://docs.travis-ci.com/user/environment-variables/
gem install travis (or brew install travis on macOS)
    travis login --pro
    travis encrypt MY_GIT_PAT=super_secret --add env.global

