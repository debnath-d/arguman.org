![Argüman.org](https://raw.githubusercontent.com/arguman/arguman.org/master/logo/logo-v2.png)
----
[Arguman.org](https://arguman.org) is an argument analysis and [mapping](https://en.wikipedia.org/wiki/Argument_map) platform.

## How does it work

Users assert contentions to be discussed, supported, proved, or disproved, and argue with premises using because, but, or however conjunctions.

![image](https://raw.githubusercontent.com/arguman/arguman.org/master/example-argument.png)

## Benefits

Critical thinking is the intellectually-disciplined process of actively and skillfully conceptualizing, applying, analyzing, synthesizing, and/or evaluating information gathered from, or generated by, observation, experience, reflection, reasoning, or communication as a guide to belief and action. In its exemplary form, it is based on universal intellectual values that transcend subject matter divisions: clarity, accuracy, precision, consistency, relevance, sound evidence, good reasons, depth, breadth, and fairness.

Basis of critical thinking is arguments. Assessment is done over argument, argument premises, promotives, and corruptives.

You can think of argument mappings as visual hierarchy mappings.

Arguman.org’s aim is to map arguments successfully through the efforts of many users.

![](https://raw.githubusercontent.com/arguman/arguman.org/master/argument-map.png)
https://www.wikiwand.com/en/Argument_map

## Who are we

arguman.org is an open source project which is developed by the community. If you want to contribute technically or intellectually please don’t hesitate.
Check [contributing documentation](CONTRIBUTING.md) for hints how to do it.


## Installing Arguman

If you are not sure which method to choose, choose the first one - Docker.

### Docker

- Fetch repository by `git clone git@github.com:arguman/arguman.org.git`
- Make sure you have [docker](http://docker.io) and [docker-compose](https://docs.docker.com/compose/install/) installed and working
- create `settings_local.py` from `settings_local.py.ex` under `main` folder
- if you are using docker-machine or running docker on vagrant make sure you set proper addresses on `settings_local.py`
- run `docker-compose up` under main project directory where `docker-compose.yml` is

### Vagrant

Go to [Docs: Vagrant Installation](docs/vagrant_installation.md) for details.
 
### Manual install

Go to [Docs: Installation](docs/installation.md) for details.

## Contributing

Go to [Contributing documentation](CONTRIBUTING.md) for details on how to contribute code or add new [translations](CONTRIBUTING.md#translations).

## Subreddit
<https://www.reddit.com/r/arguman>

## License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
