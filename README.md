
#  Kitchen Orchestrator

Main Kitchen project

![architecture](./docs/assests/arquitecture.svg)


## Authors

- [@Miguel Quevedo](https://github.com/leugin)


## Projects
### Backend Packages
| Project                                                | description         |
|--------------------------------------------------------|---------------------|
| [kitchen-core](https://github.com/leugin/kitchen-core) | main package        |
| [remote-auth](https://github.com/leugin/remote-auth)   | external auth login |

### Backend services
| Project                                                | description          |
|--------------------------------------------------------|----------------------|
| [kitchen-auth](https://github.com/leugin/kitchen-auth) | auth provider        |
| [kitchen](https://github.com/leugin/kitchen)           | kitchen management   |
| [kitchen-warehouse](https://github.com/leugin/kitchen) | warehouse management |


### Admin services
| Project                                                  | description      |
|----------------------------------------------------------|------------------|
| [kitchen-admin](https://github.com/leugin/kitchen-admin) | management panel |


### Conector
| Project                               | description       |
|---------------------------------------|-------------------|
| [rabbitmq](https://www.rabbitmq.com/) | connector service |

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Install
#### Docker
```bash
docker compose -f docker-compose-init.yml
```


## Start
#### Docker
```bash
docker compose up -d
```


