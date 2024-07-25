# Keycloak Theme World-Direct

## Development

* Start keycloak, with theme caching disabled:

  ```shell
  podman machine start
  podman-compose up -d
  ```

* <http://localhost:8080/>, Login: `admin`, `dev_only`
* TODO: realm-import, with realm having the theme pre-selected for easy development
