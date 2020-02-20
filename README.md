# Automated Github Releases

## :heavy_check_mark: Prerequisites
TBD

## :gear: Installation 
TBD


## :wrench: How to use
Run `new-release` followed by the desired version bump type: `major`, `minor`, `patch`. 

For example, the following will allow you to create tag bumped by a minor version:

```bash
$ new-release minor
```

### Target commitish option

The default commitish value where the Git tag is created from is the `master` branch. To specify a different commitish value, run with the `--target_commitish` option. For example:

```bash
$ new-release minor --target_commitish eb6bc2c21ff896f159da74608f0a96330419a3e5
```

## :question: Usage help

For usage help, run:

```bash
$ new-release --help
```


