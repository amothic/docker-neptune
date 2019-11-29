# docker-neptune

Imitate aws neptune for local dev

## Usage
```console
docker run --rm -p 8182:8182 amothic/neptune

curl "localhost:8182/gremlin?gremlin=g.V()"
```

## License
[MIT License](LICENSE)
