# Make Great

## Development workflow

1. Start server with `bin/server`
2. Make changes in the `source` folder
3. Check out results in the browser on `http://localhost:4567`

## Manual deploy to Github Pages

Setup correct git remote and target host using environment variable:

```bash
export GIT_REMOTE=git@github.com:EmmaKhayrullina/make-great.git
export TARGET_HOST=example.com
```

Run `bin/deploy`

## Semaphore integration

### Test build

You can use [Semaphore](https://semaphoreci.com) to make sure your source code
will be built successfully.

Add these build commands:

```bash
bin/setup
bin/build
```
