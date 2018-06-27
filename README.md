Prodrivers Bootswatch
==========

Prodrivers Bootswatch is a bootstrap theme based on the Cosmo [Bootswatch](http://bootswatch.com) theme, an open source theme for [Bootstrap](http://getbootstrap.com/).

Usage
-----
Download the `bootstrap.min.css` file associated with a theme and replace Bootstrap's default stylesheet. You must still include Bootstrap's JavaScript file to have functional dropdowns, modals, etc.

You can import a theme into your styles using either LESS or SASS.

LESS:

```less
@import "bootstrap/less/bootstrap.less";
@import "bootswatch/theme/variables.less";
@import "bootswatch/theme/bootswatch.less";

```


Customization
------
Prodrivers Bootswatch is open source and you’re welcome to modify the theme.

The theme consists of multiple LESS files. `variables.less`, which is included by default in Bootstrap, allows you to customize [these settings](http://getbootstrap.com/customize/#less-variables). `bootswatch.less` introduces more extensive structural changes.

Check out the [main page](http://bootswatch.sources.prodrivers.fr/) for more details on building your own theme.

Thanks
------
[Thomas Park](http://github.com/thomaspark) for [Bootswatch](https://github.com/thomaspark/bootswatch).

[Mark Otto](https://github.com/mdo) and [Jacob Thornton](https://github.com/fat) for [Bootstrap](https://github.com/twbs/bootstrap).

[Jenil Gogari](http://www.jgog.in/) for his contributions to the Flatly theme.

[James Taylor](https://github.com/jostylr) for [cors-lite](https://github.com/jostylr/cors-lite).

[Corey Sewell](https://github.com/cjsewell) for SASS conversion.


Copyright and License
----
Copyright 2014-2016 Thomas Park
Copyright 2016-2018 Prodrivers

Code released under the MIT License.
