# hypha.coop

[![Build Status](https://travis-ci.org/hyphacoop/hypha.coop.svg?branch=master)](https://travis-ci.org/hyphacoop/hypha.coop)

This repository holds the source code and static assets of [hypha.coop][website]. Based on a modified version of an existing template codebase (see below).

## Technologies Used

- [**Bootstrap.**][bootstrap]
  - [**Template: Coming Soon.**][template] a simple coming soon theme created by [Start Bootstrap][start-bootstrap].
- [**Jekyll.**][jekyll]
- [**Travis CI**.][travis]

## :computer: Development

1. Clone repository: `git clone https://github.com/hyphacoop/hypha.coop.git && cd hypha.coop`
2. Install Bundler gem: `gem install bundler`
3. Install dependancies: `bundle install`
4. Run locally: `bundle exec jekyll serve`
5. Visit your `localhost` on port `4000`: http://localhost:4000 or http://127.0.0.1:4000

## :rocket: Deployment

We auto-deploy `master` branch to [hypha.coop][website] via Travis CI. (See [`.travis.yml`][ci-conf])

## :copyright: License & Copyright

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](./LICENSE) license.

Additional customizations by [@ASoTNetworks](https://github.com/ASoTNetworks) and [@patcon](https://github.com/patcon).

<!-- Links -->
   [website]: https://hypha.coop
   [bootstrap]: http://getbootstrap.com/
   [template]: https://github.com/BlackrockDigital/startbootstrap-coming-soon
   [jekyll]: https://example.com
   [travis]: https://example.com
   [ci-conf]: /.travis.yml
   [start-bootstrap]: http://startbootstrap.com/
