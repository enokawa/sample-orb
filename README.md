# sample-orb

## Install `circleci`

```shell
$ brew install circleci
```

## Create CircleCI API token

https://circleci.com/account/api

## Set API token

```shell
$ circleci setup
```

# Allow Uncertified Orbs

```
https://circleci.com/gh/organizations/<your-organizations>/settings#security
```

## Create namespace

```shell
$ circleci namespace create enokawa github enokawa
```

## Create orb

```shell
$ circleci orb create enokawa/sample-orb
```
