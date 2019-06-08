# What is this?

This repo is provide docker image for Ruby on Rails.

## Modify files

- Dockerfile

if you want to use other than ruby 2.6.3, modify Dockerfile FROM setting.

- Gemfile

if you want to use other than Rails 5.2.3, modify Gemfile.

## Create docker image

```
git clone https://github.com/dozonot/rails-on-docker.git
cd rails-on-docker
docker image build -t rails:5.2.3 .
```

enjoy!
