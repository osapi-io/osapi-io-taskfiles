# Remote Taskfiles

[Remote Taskfile][]s used by [osapi-io][] projects.

## Usage

```yaml
version: '3'

includes:
  go: https://raw.githubusercontent.com/osapi-io/osapi-io-taskfile/refs/heads/main/go.yml
  bats: https://raw.githubusercontent.com/osapi-io/osapi-io-taskfile/refs/heads/main/bats.yml
```

## License

The [MIT][] License.

[Remote Taskfile]: https://taskfile.dev/experiments/remote-taskfiles/
[osapi-io]: https://github.com/osapi-io
[MIT]: LICENSE
