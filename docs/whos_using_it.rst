Whos using it
=============

.. image:: images/logo-globocom.png


http://www.globo.com - globo.com uses thumbor to generate dynamic images
through all products across the portal. Around 15 billion images served
per month.

.. image:: images/properati-logo.png

http://www.properati.com.ar/ - properati is also using thumbor to
generate several different sizes of their properties photos, using smart
cropping to get the best possible thumbnails.

    Thumbor made our lives better.

    At Properati.com.ar we care a lot about user experience.

    When our design team came up with a beautiful design that included
    thumbnails of 5 different sizes and specific cropping specs, instead
    of enhancing our home-made, simple thumbnail-generator process we
    moved to Thumbor and now, we cannot live without it.

    Thanks a lot!

.. image:: images/yipit.png

http://yipit.com/ - yipit now uses thumbor behind the CloudFront
`CDN <http://en.wikipedia.org/wiki/Content_delivery_network>`__ at
Amazon. Their detailed experience with setting up thumbor can be seen at
`this blog
post <http://tech.yipit.com/2013/01/03/how-yipit-scales-thumbnailing-with-thumbor-and-cloudfront/>`__.

    Thumbor allows Yipit to iterate quickly on new designs without
    having to worry about introducing new image sizes.

    On demand image generation was just too slow when integrated into
    our application servers, but Thumbor makes it possible.

    No more going through old images and creating new thumbnails before
    we can roll out a new design!

    Our initial Thumbor installation took less than an hour to set up,
    and we haven't had to spend much time thinking about it since then.

    Zach Smith - CTO

.. image:: images/oony.png

http://oony.com is using thumbor to serve thumbnail images behing
Amazon's Cloudfront CDN.

    We've previously adapted the size of the thumbnails to what was
    required by our design team, forcing us to have many different
    versions of the images we have on our site.

    With Thumbor we don't have to worry about this anymore, and we can
    quickly iterate and make changes to our layouts serving the optimal
    image format each time.

    Thumbor is awesome!

.. image:: images/viadeo.png

The Viadeo Group owns and operates professional social networks
around the world with a total membership base of over 55 million
professionals. Professionals use the networks to enhance their
career prospects, discover business opportunities and build
relationships with new contacts as well as to create effective
online identities.

    With headquarters based in Paris, the Group currently has over 450
    staff with offices and teams located in 10 countries.

    `Viadeo <http://viadeo.com>`__ is using Thumbor more and more. We
    used to have some home-made Java code to deliver images from
    http://www.viadeo.com. This code is still alive for some parts of
    our site.

    Since the end of summer 2013, Thumbor is a reality at Viadeo. First
    via IOS application for member's profile photos, then our news
    platform uses it for new parts of the site, taking more and more
    place and also some Android applications.

    Thumbor helps us in migrating and decoupling applications from our
    storage backend. We were able to move from NFS (centralized and very
    sensitive to high loads) to a distributed storage like HBase, using
    a `hbase storage
    plugin <https://github.com/dhardy92/thumbor_hbase>`__. Using the
    same technique of lazy loading (via Storage cache in thumbor) we can
    imagine changing our image's storage at our convenience should
    apache HBase start to show deficiencies. This is really comfortable
    for Ops.

.. figure:: https://photos-6.dropbox.com/t/0/AAB3D6eKY8kwYj31vVM9-OzqK-KZZNlZHzPKAHLyKJI2JQ/12/1991264/png/2048x1536/3/1403200800/0/2/threadless.png/EchOaLOlADj4-3Hdi-Apta8dr0o9EgUXvJBFvDe7olY
   :alt: threadless

`TypeTees <https://www.threadless.com/typetees>`__ is an easy-to-use
iPhone app that lets you speak your mind by putting your super witty
slogan into an original tee and order it immediately.

    We use Thumbor to generate mobile thumbnails directly from the same
    large images that are sent to the t-shirt garment printer. It
    requires dealing with masks, feature trimming, transparent images,
    and replacing backgrounds to give users an easy-to-see preview of
    the t-shirt.

    Thumbor made this possible and simple without having to write an
    image processor from scrap.

    TypeTees was developed by www.prolificinteractive.com and you can
    learn more about how thumbor helped them at `their engineering blog
    post <http://prolificinteractive.com/blog/2014/05/29/threadless-typetees-neat-and-easy-thumbnails-using-thumbor-and-php/>`__.

How to add my site or product here
----------------------------------

If you are using thumbor and your site or product is not listed here,
please create an issue and we'll include your logo and a short
description on how you are using it here.
