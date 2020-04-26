# BLT Project

This is a Composer-based installer for a Drupal 8 project utilizing [BLT](https://github.com/acquia/blt). This project 
is forked from acquia/blt-project. However, does not include the Acquia Cloud connection module, or the Acquia Lightning 
Drupal install profile. Also, this package includes to commonly used modules, and other tools.


## Get Started

To create a new Drupal 8 project with BLT included, nmangold style.

```
composer create-project --no-interaction nmangold/blt-project my_project
```

## Branches

Tags of blt-project will build a new project using the latest stable tag from BLT. E.g.,

`composer create-project nmangold/blt-project:^10.0.0-alpha1 --no-interaction my-project`

The 10.x branch of blt-project will build a new project using the 10.x branch of BLT. E.g.,

`composer create-project nmangold/blt-project:10.x-dev --no-interaction my-project`

## Contributing

This is a subtree split from the main BLT project. Do not open pull requests or make any other changes directly to blt-project.

## License

Copyright (C) Nicholas Mangold

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 2 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
