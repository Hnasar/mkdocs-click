# cli

Main entrypoint for this dummy program

**Usage:**

```
cli [OPTIONS] COMMAND [ARGS]...
```

**Options:**

```
  --help  Show this message and exit.
```

**Subcommands**

- *bar*: The bar command
- *foo*: *No description was provided with this command.*

## bar

The bar command

**Usage:**

```
cli bar [OPTIONS] COMMAND [ARGS]...
```

**Options:**

```
  --help  Show this message and exit.
```

**Subcommands**

- *hello*: Simple program that greets NAME for a total of COUNT times.

### hello

Simple program that greets NAME for a total of COUNT times.

**Usage:**

```
cli bar hello [OPTIONS]
```

**Options:**

```
  --count INTEGER  Number of greetings.
  --name TEXT      The person to greet.
  --help           Show this message and exit.
```

## foo

**Usage:**

```
cli foo [OPTIONS]
```

**Options:**

```
  --help  Show this message and exit.
```
