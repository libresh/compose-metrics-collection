To get started you'll need the following:

Clone this folder in `/system` folder.

First your system needs to have a proper hostname where it will expose those metrics.
Make sure `echo $HOSTNAME` outputs a proper hostname that will be exposed publicly.

Then create the `htpasswd` that will protect your service behind a username password.
(to avoid Internete scraping your server metrics)

And finally:

```
libre start
libre enable
```
