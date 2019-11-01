# fteychene personal blog

Pseronal blog using Jekyll

This site use [`{ Personal } Jekyll Theme for Jekyll`](https://github.com/le4ker/personal-jekyll-theme/)

## Usage

To create an article push a new file in `_posts` folder.  
The file should have the `YYY-MM-DD_name.md` pattern.

All the content until a `<!--break-->` ill be printed on index if it's the latest post.

### How to run locally

First, you need to install jekyll and the dependencies of { Personal } by running:

```shell
./scripts/install
```

Then, you can build and serve your website by simply running:

```shell
./scripts/serve-production
```

To serve across lan (requires su to forward the port 4000 over lan):

```shell
./scripts/serve-lan-production
```

### Docker

Run using Docker:

```
docker run --rm -it -p 4000:4000 -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll serve --watch --host "0.0.0.0" --config _config.yml,_config.dev.yml
```

Run using Docker with Docker Compose:
```
docker-compose up
```