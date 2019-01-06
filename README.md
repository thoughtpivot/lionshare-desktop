# Lionshare Desktop

![1-diwz_x9p3c86sfo-gydi5a](https://cloud.githubusercontent.com/assets/31465/22240931/0e1f9c58-e1d2-11e6-9c28-d7cbd3b3f03b.png)

Lionshare is a simple portfolio visualiztion application that helps gives insight into your investmnt performance. By design it will run on macOS, Windows and Linux desktop environments. Although at present we discourage any attempts to run a stable version on any platform other than macOS, for now.

## Key Features

Leveraging a highly responsive and intuitive interface, it gives you near real-time insight into the performance of your digital asset performance while keepings the featureset simple, yet, informative.

Initially we've focused on some the most highly utilized digital asset exchanges in the world, and at present pulls market data from coinmarketcap. The leader in providing up-to-date information with respect to the ever changing landscape of digital currency.

## Installation

### Lionshare Stable

Until we have stable releases available our website, you can download stable releases directly from our GitHub repository...

    npm -i  https://github.com/lionsharecapital/lionshare-desktop/archive/v1.1.0.tar.gz

### Lionshare Beta

If you're interested in the cutting edge features being developed by the team which are not yet ready for a formal release to the greater public, feel free to snag the latest revision from our GitHub repository...

    npm -i -g lionsharecapital/lionshare-desktop

### Lionshare Development

For those of you interested in contributing to the project, or, just want to tinker with the code, you can clone our GitHub repository...

    $ git clone git@github.com:lionsharecapital/lionshare-desktop.git
    $ cd lionshare-desktop
    $ yarn

### Lionshare API

There is a fairly straight forward library available on NPM called "lionshare" which allows a developer to take advantage of some of the efforts we've made to bring you a solid API backend for the Lionshare suite of products. They can be installed easily via the node packagemanager. Detailed instructions on how to use the library are included with the package...

    npm -i lionshare


### Starting Lionshare

Running Lionshare is pretty straight forward. From the root directory where you installed it, siimply type the following command...

    yarn start

## About

Lionshare is an open source project created by [Ben Jennings](https://twitter.com/benjennin_gs), [Jori Lallo](https://twitter.com/jorilallo) and [Maksim Stepanenko](https://twitter.com/maksim_s).

## What Do Others Say ?

[**Blog: Announcing Lionshare**]
(https://medium.com/@jorilallo/announcing-lionshare-541daf082160)

## Donate

Lionshare is an open source side project. To support development and keep our server running, you can donate using Bitcoin and Ethereum:

- Bitcoin: `14cYsomReqcsznbKTuW6Mh91uZm2j2AF5B`
- Ethereum: `0xbBC664b891D6Fc7EBF516594D690e370C5C32A9f`

## FAQ

**When will Lionshare support < your favorite coin >?**

Right now we're supporting coins with the most market cap listed on GDAX and Poloniex. If we're not yet supporting your favorite coin, please create an issue to [lionshare-api](https://github.com/lionsharecapital/lionshare-api/issues) repository or upvote an existing one :+1:

**Does my portfolio leave my computer?**

No, Lionshare is completely client-side and doesn't hold any keys. We take security very seriously and all our communication happens over HTTPS. All code is open source.

**How will you make money?**

We won't, this is a side project.

**When can I have a Linux, Windows, iOS, etc version?**

We are eager to say that we're gaining real ground on supporting Windows and Linux desktop environments. As I'm sure you are all well aware, we have a highly useful mobile version for iOS now available on the App Store.  We will keep the community posted as we continue to expand our supported platforms.

## License

[MIT](https://opensource.org/licenses/MIT)
