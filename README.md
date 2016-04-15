# Heather for Hugo

A Hyperminimal J̶e̶k̶y̶l̶l̶ Hugo Theme

http://hbpasti.github.io/heather-hugo/

## About Heather

[Heather](//jxnblk.com/Heather/) is hyperminimal theme
for [Jekyll](//jekyllrb.com) created by Brent Jackson
([jxnblk](//jxnblk.com/)).

## About J̶e̶k̶y̶l̶l̶ Hugo

[Hugo](//gohugo.io) is a (very) fast static site generator written in Go.

Compatible with hugo [0.15.0](http://gohugo.io/meta/release-notes/)

## Get Started

Once you have Hugo set up, create your blog with `hugo new` and then
add the heather-hugo theme to the `themes` directory.

You can just download and extract it there or add it as a submodule
with:

    git submodule add https://github.com/hbpasti/heather-hugo themes/heather-hugo

Then edit your blog's config file to use heather-hugo theme:

- `config.toml`

    ``` toml
    theme = "heather-hugo"
    ```

- `config.yaml`

    ``` yaml
    theme: "heather-hugo"
    ```

For example, a minimal YAML config file looks like this:

    title: "Heather"
    baseurl: "http://localhost:1313"
    languageCode: en-us
    theme: heather-hugo

    permalinks:
      post: /:year/:month/:title/

    taxonomies:
      tags: ["meta", "theme", "blog"]

    params:
      description: A Hyperminimal J̶e̶k̶y̶l̶l̶ Hugo Theme
      author: 
        name: "Hbpasti"
        email: "your@email.com"
      readMoreLabel: "Read more"
    ...

---

MIT License
http://opensource.org/licenses/MIT
