# totp
A tiny command line utility to generate OTP tokens

## Build and install

Clone the repository:

    $ git clone https://github.com/angt/totp
    $ cd totp

Then, run as `root`:

    # make install

As usual, you can customize the destination with `DESTDIR` and `prefix`.

## Usage

It has been thought for [secret](https://github.com/angt/secret),
maybe it will be directly integrated in a future version, in the meantime:

### Add a new TOTP key

    $ echo -n JBSWY3DPEHPK3PXP | base32 -d | ./totp

---

For feature requests and bug reports,
please create an [issue](https://github.com/angt/totp/issues).
