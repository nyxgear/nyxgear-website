# nyxgear-website

Source code of [nyxgear.com](https://nyxgear.com) website.

Developed using:

- [Hugo](https://gohugo.io/) static site generator.
- [GitHub Actions](https://github.com/features/actions) for continuous deployment
- [Netlify](https://www.netlify.com/) as hosting provider

## Quickstart

*Requirements:*

- git
- docker

Clone the repo, and start the Hugo server:

```bash
git clone --recurse-submodules git@github.com:nyxgear/nyxgear-website.git

cd nyxgear-website

docker run --rm -it \
  -u $(id -u):$(id -g) \
  -v $(pwd):/src \
  klakegg/hugo:0.93.2 server
```

Check local preview: <http://localhost:1313>

### Create a new post

```bash
docker run --rm -it \
  -u $(id -u):$(id -g) \
  -v $(pwd):/src \
  klakegg/hugo:0.93.2 new --kind post posts/my-new-post.md
```
The `--kind` option uses the [archetype](https://gohugo.io/content-management/archetypes/) `./archetypes/post.md` as a template.

Instead, to create a bundle post:

```bash
docker run --rm -it \
  -u $(id -u):$(id -g) \
  -v $(pwd):/src \
  klakegg/hugo:0.93.2 new --kind bundle-post posts/my-new-post
```

