---
title: 'New Personal PGP Key'
date: 2024-07-16
permalink: /posts/2024/07/new-personal-pgp-key/
tags:
  - cybersecurity
---

Around when I started at the CERT Coordination Center in 2014, I created a personal PGP key for secure email communications to handle vulnerability reports. With that key going on a decade old, it seemed appropriate to retire it and create a newer key. Especially since newer crypto algorithms like ECC are becoming more popular, with the older RSA (possibly?) beginning to phase out. [Trail of Bits](https://blog.trailofbits.com/2019/07/08/fuck-rsa/) for example has a blog post arguing to stop using RSA and instead adopt ECC, in particular Ed25519, for signing keys.

So I now have a new PGP key, signed by my previous key. Further information on the keys is below.

I intend to use the new key primarily for digital signatures such as signing code commits and releases on my personal projecs. It is also available for use in sending secure email about potential security vulnerabilities. Not that I expect (or recommend) my experimental personal projects to be widely used in any realistic environment. But it's more of a "eat your own dogfood" situation; I recommend vendors be prepared to handle coordinated vulnerability disclosure so it is also good for me to practice the process myself!

New PGP public key to use going forward can be [downloaded](http://gwasser.github.io/files/pgp/gwassermann_0x29725C11_public.asc) or copy/paste from below:

    -----BEGIN PGP PUBLIC KEY BLOCK-----

    mDMEZo41JRYJKwYBBAHaRw8BAQdAmJ2Y9gF0rpC/7yGHtZaX8Ak2ePd/TGhpJ2pW
    8fU0jjW0JUdhcnJldCBXYXNzZXJtYW5uIDxnd2Fzc2VyQGdtYWlsLmNvbT6ImQQT
    FgoAQRYhBOLKKsfxiCrmtB0nWabWQTUpclwRBQJmjjUlAhsDBQkLSQFbBQsJCAcC
    AiICBhUKCQgLAgQWAgMBAh4HAheAAAoJEKbWQTUpclwRUXcA/349uWQ779PCjJZ2
    pvQq1ZMnXwuqBn+Y8++s47kphSieAP9ihuA2HEY3IXZxhh/zlsZTEVZNyTMg2GUb
    GbK2rWBuCIkCMwQQAQgAHRYhBLTIz/Gle4e8L9JQuiHaJBn6wziuBQJmjjYRAAoJ
    ECHaJBn6wziuDboQAIZ/84tRRxPmzG/u1nbUd/CuDBm12nBBBCTUAdS+60OMxSQu
    uH/zgb0T0qBmXnZjjlrNrNxYiJoPw9FcJxahoOfaaBI/I0XRZjkuieCV2spcmQ1W
    YMaR0mbEuQqyewgtqm3RpsiCGzxU/yoLbgFYyUTIlt66Q5tIP1OpOy1cWPLk6MTq
    AvDlXbIwfv+/cH/Q7DJWEfPhyf5nowixSWngYdjf03v/D9ScOUPkQSv7/1ACaLLF
    ln4CtSFF2mzKy1m+OdhpNNXp33iJLhXwZ61/R4LAfyDsxNkRxbmpUJn5XLiefWlL
    Mpe/M/GcrWcLm7NAxWYdjf9kKhW2uOfBJUXKeOVMoXNcpmgKwEkQ+C1bW/bX2MvQ
    6VpAZhg+PVfv4QlXlMgTBDHW4ZLBdh1hfN28matdgoMYkN6xzNgLFGW9P5DCLeGz
    ARhjHhs65IhLenwWsXV8GVOfjJ+GfNVGJB7pes0XzqBq7/en25aRLjIp4ma2oaC7
    dsbRC48YqL7+2M6/ZMm0KSLVnug27EcrDkBUzScUeHB6y7tU3MVuslB21ovu3tko
    mX+lc+RosrlkA0zxe1X4eA8xIFnKQPt8OXsxyTbWBxDV3ihv8j7aMii4bo5pQl0q
    3SDQ5AUqUS2WccfmG90VT4DQN4VJTRYBsBZins6i1wg6SOCm3dRop9EZ9LdQuDgE
    Zo41JRIKKwYBBAGXVQEFAQEHQN8WFtTfm8ZCLx+Ay4QzItxkWFgDcl5coDTB1528
    m+o2AwEIB4h+BBgWCgAmFiEE4soqx/GIKua0HSdZptZBNSlyXBEFAmaONSUCGwwF
    CQtJAVsACgkQptZBNSlyXBHG8AEAq6MSezsFxTBtuxsK8c/seabHOAwBIi/AFP8t
    tzcARsQBAOwqewXBw+jH7EpciaL/Zy43qzdX0vjdoTA9b0m0m0gC
    =EwtH
    -----END PGP PUBLIC KEY BLOCK-----

and the fingerprint to verify:

    pub   ed25519 2024-07-10 [SC] [expires: 2030-07-10]
          E2CA 2AC7 F188 2AE6 B41D  2759 A6D6 4135 2972 5C11

I expect this key on public key servers soon.
