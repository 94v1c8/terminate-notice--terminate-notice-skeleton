# Terminate Notice - Skeleton

___Handle your AWS Spot Instance Actions with terminate-notice___

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->[![All Contributors](https://img.shields.io/github/all-contributors/terminate-notice/terminate-notice?color=ee8449&style=flat-square)](#contributors)

## About

This is not actually a plugin for [Terminate Notice](https://terminate-notice.github.io)
but is instead a templated directory structure for you to use. Clone this to your local
machine and then delete the .git directory. Run `git init` and then do a replace for:

- YOUR_PLUGIN (like `announce`, `slack` or `datadog`)
- YOUR_REPO (assumed to be `terminate-notice-${YOUR_PLUGIN}`)
- YOUR_ORG
- YOUR_NAME

This includes the files in `etc/terminate-notice.conf.d`, `usr/share/doc` and
`usr/share/terminate-notice/actions/`.

You'll also need to rename:

- `/_EXAMPLE.github` to `/.github`
- `/_EXAMPLE.README.md` to `/README.md`
- `/_EXAMPLE.all-contributorsrc` to `/.all-contributorsrc`

Next, you need to update the values of: `DESCRIPTION` and `MAINTAINER` in `.github/workflows/release.yml`

Lastly, put your own plugin code into `usr/share/terminate-notice/actions/XX-YOUR_PLUGIN`

Commit, tag (using [Semantic Versioning](https://semver.org/) is recommended) and push your code to Github.

If you want to advertise your plugin, please feel free to do so, over at the
[project home repo](https://github.com/terminate-notice/terminate-notice.github.io/). If you want to
contribute your plugin to the organisation, please [get in touch](mailto:jon@sprig.gs)!

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://jon.sprig.gs/"><img src="https://avatars.githubusercontent.com/u/228671?v=4?s=100" width="100px;" alt="Jon "The Nice Guy" Spriggs"/><br /><sub><b>Jon "The Nice Guy" Spriggs</b></sub></a><br /><a href="https://github.com/terminate-notice/terminate-notice-skeleton/commits?author=JonTheNiceGuy" title="Code">💻</a> <a href="#ideas-JonTheNiceGuy" title="Ideas, Planning, & Feedback">🤔</a> <a href="#plugin-JonTheNiceGuy" title="Plugin/utility libraries">🔌</a> <a href="#tool-JonTheNiceGuy" title="Tools">🔧</a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td align="center" size="13px" colspan="7">
        <img src="https://raw.githubusercontent.com/all-contributors/all-contributors-cli/1b8533af435da9854653492b1327a23a4dbd0a10/assets/logo-small.svg">
          <a href="https://all-contributors.js.org/docs/en/bot/usage">Add your contributions</a>
        </img>
      </td>
    </tr>
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!