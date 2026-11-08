.. title: Open Source Summit Europe 2026
.. slug: oss-eu-2026
.. date: 2026-10-27 20:06:28 UTC
.. tags: conferences, open source, python
.. category: 
.. link: 
.. description: 
.. type: text
.. previewimage: /images/oss-eu-2026-prague-congress-centre.jpeg

Earlier this month I spent a few days at `Open Source Summit Europe
<https://events.linuxfoundation.org/open-source-summit-europe/>`_ in Prague.
It was my first time at the summit, and there was a lot to take in. There were
dozens of tracks and co-located events over three days at the Prague Congress Centre.
Many thanks to the `Sovereign Tech Agency <https://www.sovereign.tech/>`_ for
sending me as part of the `Sovereign Tech Fellowship
<https://www.sovereign.tech/programs/fellowship>`_.

Here are a few things that stuck with me.

.. figure:: /images/oss-eu-2026-prague-congress-centre.jpeg
   :align: center
   :alt: A morning view of the Prague Congress Centre, over the Nusle Bridge,
         with coaches crossing it and a large hotel block in the distance.

   A view of the Prague Congress Centre, from my daily walk over the Nusle Bridge.


Documentation
=============

I spent a good chunk of my time in the documentation track.
I talked with other documentation theme developers about accessibility.
It turns out we're all struggling with it in slightly different ways. We also discussed
internationalisation and switching documentation frameworks. The latter is
something I often think about for the Python documentation, as we chip away
at problems in `python-docs-theme
<https://github.com/python/python-docs-theme>`_ and the translations...

Unsurprisingly, the liveliest discussions were about AI. We talked about how
*we*, as documentation writers, can use it, but also about the more uncomfortable
question of writing documentation *for* AI. What changes when more of our
readers are agents rather than people? I don't think anyone in the room had
a settled answer to that one. ;-)


Security
========

The security track was fairly bleak. I often complain about the flood of
low-quality, machine-generated vulnerability reports we get in CPython, and
I heard much the same from other projects. The consensus seemed to be that
the only realistic way to keep up with AI-generated reports is to use AI
ourselves.

I also learned a lot more about the European Union's `Cyber Resilience Act
<https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act>`_ and
what it actually means for free and open source projects (like mine!).
I found it especially useful to learn what we *don't* have to do, and what
we could choose to do to help downstream vendors meet their obligations,
such as publishing an `OpenSSF Scorecard <https://scorecard.dev/>`_.


OpenSSF
=======

Speaking of which, I met a number of people from the `OpenSSF
<https://openssf.org/>`_ and heard about what they're working on. I'd like to
get involved, and they walked me through how to join.

I also met people running the security incident response teams of
other critical open source projects! We compared notes on how we each handle
reports, and swapped ideas on how to improve our practices. It's reassuring,
and I suppose a little worrying, to find that everyone is dealing with the same
things.


RISC-V
======

I spoke with several companies working on RISC-V,
one of which offered to help CPython by providing some `Buildbots
<https://buildbot.python.org/>`_. More hardware, and more unusual hardware, in
the Buildbot fleet is always welcome. :-)


The future of open source
=========================

A recurring theme across the summit was sustainability, and in particular
maintainer burnout. One session covered how burnout develops, what the early
signs are, and why maintainers need mental health support. I came away
feeling that maintainers need to stand up for
themselves, because nobody else is going to do it for them. `Miranda Heath
<https://mirandaheath.website/>`_ has written about this far better than I can.


Turtle
======

I also happened to meet a developer working on `turtlegrove
<https://github.com/Pascal71/turtlegrove>`_, a slightly different take on
turtle graphics. We spent a while comparing our implementations and sharing
ideas on how to improve each of them.


Proofs of personhood
====================

One of the more forward-looking talks was about cryptographic proofs of
personhood: how to verify that a contributor is a person, and/or that an agent
is acting on behalf of a specific person. It covered the mechanisms the Linux
kernel already uses and some proposed improvements. Given the direction things
are heading, I suspect this is going to matter to Python sooner rather than
later.


Working with LLMs
=================

My own use of LLMs is still fairly basic, so I picked up a few ideas for
getting more out of them and running agents securely. Someone introduced me
to `nono <https://nono.sh/>`_, a tool for sandboxing AI agents, which I've
already started using.


Prague in the evenings
======================

It was also my first time in Prague, so once the talks wound down each day I
went out to explore the beautiful city. The Congress Centre sits up on the Nusle
plateau, and from there it's a short-ish walk or metro ride down into the heart
of the city. I spent my evenings wandering across the Charles Bridge, up to the
castle for the view back over the river, and through the Old Town's streets.

.. figure:: /images/oss-eu-2026-jiriho-z-podebrad.jpeg
   :align: center
   :alt: Jiřího z Poděbrad square at night: the floodlit Church of the Most Sacred Heart of Our Lord, with its huge glass clock face, and the Žižkov TV Tower lit up behind it.

   Jiřího z Poděbrad square in Vinohrady, with Plečnik's Church of the Most
   Sacred Heart and the Žižkov TV Tower behind it.

Three days wasn't nearly enough, for the summit or for the city, and I'd happily
go back for either.
