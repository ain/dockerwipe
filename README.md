__DISCONTINUED__. Use `docker system prune -a --volume` instead. See also [docker system prune](https://docs.docker.com/engine/reference/commandline/system_prune/).

# dockerwipe

Utility to clean up your Docker stack and claim back valuable disk space.

## Features

- Removes dangling volumes and images with single command (default)
- Removes all containers (optional)

## Installation

TBD.

## Usage

    $ dockerwipe [-f]

## Options

```
-f      Remove all containers (in addition to dangling volumes, images)
```

## Licence

Copyright © 2019 Ain Tohvri. Licenced under [GPL-3](LICENSE).
