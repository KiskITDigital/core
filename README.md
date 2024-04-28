# Proto files for ubrato microservices

## Generate for golang

```bash
make generate.go
```

## Generate for python

```bash
make generate.go
```

## Integration

```bash
git submodule add https://git.ubrato.ru/ubrato/proto proto
echo "include ./proto/proto.mk" >> Makefile
```
