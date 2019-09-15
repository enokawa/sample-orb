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

## Create Orb

```shell
$ circleci orb create enokawa/sample-orb
```

## Create `orb.yml`

```shell
$ vim orb.yml
```

## Validate `orb.yml`

```shell
$ circleci orb validate orb.yml
```

## Publish Orb

```shell
$ circleci orb publish orb.yml enokawa/sample-orb@0.0.1
```
