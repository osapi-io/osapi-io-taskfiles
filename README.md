# Remote Taskfile

A [Remote Taskfile][] used by [osapi-io][] projects.

## Usage

```yaml
version: '3'

includes:
  go: https://raw.githubusercontent.com/osapi-io/osapi-io-taskfile/refs/heads/main/Taskfile.yml
```

### Start

To start the embedded NATS server:

```bash
$ nats-server start
```

## License

The [MIT][] License.

[Remote Taskfile]: https://taskfile.dev/experiments/remote-taskfiles/
[osapi-io]: https://github.com/osapi-io
[MIT]: LICENSE
