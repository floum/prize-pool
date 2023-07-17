# Prize Pool

A Prize Pool Calculator for tournaments

## Requirements

- go 1.20.5

## Usage

```bash
go run main.go TOURNAMENT_YAML
```

## the Tournament YAML

```yaml
entrants:
- count: 10
  entry: 30
- count: 5
  entry: 15
prizes:
  general: 0.1
  categories: 3
```
