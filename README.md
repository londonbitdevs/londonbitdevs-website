# London BitDevs

Simple Jekyll site for hosting all of the links from meetups past and future.

## Development

### Using Docker (recommended)

* Clone the repository and go into the directory
* Run `docker compose up`
* Go to http://localhost:4000

Changes are picked up automatically via the volume mount.

### Using Ruby directly

You'll need [Ruby & Jekyll](https://jekyllrb.com/docs/installation/) installed
locally. Once they're setup:

* Clone the repository and go into the directory
* Run `bundle install`
* Run `bundle exec jekyll serve`
* Go to http://localhost:4000

## Making a Post

To make a new post, make a new file in `_posts/` with a title of
`YYYY-MM-DD-title-goes-here`. At the top of the file you'll want to provide the
following information:

```md
---
layout: post # Always post
type: socratic # or whitepaper for a whitepaper series
title: "Name of the Post"
meetup: https://www.meetup.com/BitDevsLDN/events/[event id here]/
---
```

After that, it's just simple markdown. The site will auto-generate the rest.

## Changing Site Data

All site configurations are either contained in `_config.yml` or
`_data/settings.yml`. Some data is duplicated between the two due to the way
Jekyll injects variables, so be sure to update both.

## Attributions

Thanks to [LeNPaul](https://github.com/LeNPaul/jekyll-starter-kit) for the
Jekyll starter kit this was forked from.

Thanks to [BitDevsNYC](https://bitdevs.org) for the jekyll template and for
their many years of serving the New York and international Bitcoin communities ❤️❤️❤️.
