About Curious Efficiency
========================

About the site
--------------

Curious Efficiency is the intermittently updated personal website of Alyssa
Coghlan, CPython core developer, PSF Fellow, software development toolsmith,
cognitive science dabbler, and cynical idealist.

The main portion of the site is generated via
`Nikola <https://getnikola.com/>`__,
hosted on `GitHub Pages <https://pages.github.com/>`__,
and also under source control on
`GitHub <https://github.com/ncoghlan/curiousefficiency/>`__ (the repo layout is
a bit odd, since the source code wasn't originally on GitHub, and the hosting
moved to GitHub Pages first, with the source repository following much later).

Python specific technical writing tends to end up on the
`ReadTheDocs <https://readthedocs.org/>`__ powered
`Python Notes <https://python-notes.curiousefficiency.org>`__ subsite.


About the name
--------------

Curious Efficiency is actually a reframing of my original blog title,
Boredom & Laziness - the original boredomandlaziness.org URLs now redirect
here. The original site blurb on Boredom & Laziness read as follows:

   There are a couple of very, very scary things in this world.

   The first is a bored human. Bored humans have time to indulge their
   curiosity, with potentially amazing results.

   The second is a lazy human. Lazy humans can be quite inventive when it
   comes to figuring out how to do less work.

   So, here's to boredom & laziness - two of the prime movers in human progress!

"Curious Efficiency" is really just a nicer way of referring to the same
concept.

`This post </posts/2012/07/the-title-of-this-blog/>`__ goes into some
additional detail on the concepts that inspired the naming, both the original
form, and the current more conventionally acceptable phrasing.


About the author
----------------

.. image:: /files/alyssa_ce_about_pic.jpg
   :align: right

Alyssa is a CPython core developer, a Fellow of the Python Software Foundation,
and the founder of the PyCon Australia Education Seminar.

Together with Guido van Rossum, Brett Cannon, Barry Warsaw, and Carol Willing,
Alyssa served on the inaugural 2019 Python Steering Council. Alyssa's primary
activity while on the Steering Council was managing the transition of the
standing PyPA PEP delegations from Guido's position as BDFL to instead be
explicitly recorded `standing delegations from the Steering Council
<https://github.com/python/steering-council/blob/main/process/standing-delegations.md>`_.

She is the author or co-author of several accepted Python Enhancement Proposals
(including PEP 453, which saw the ``pip`` installer bundled with Python 3.4+,
PEP 466, which saw several key Python 3 network security enhancements backported
to the Python 2.7 series, and PEP 538, which updated CPython to coerce the
legacy ASCII-based C locale to a suitable UTF-8 based locale when one is
available), and has also accepted a number of PEPs on Guido van Rossum's behalf
as BDFL-Delegate.

Alyssa changed her name from Nicholas (Nick) Coghlan in August 2023, so
articles, videos, and archived posts from previous years will still use her
birth name. She mostly goes by Alyssa, but will also answer to Lyse and Nic (now
the short form of her middle name rather than her first name).

Alyssa was the default BDFL-Delegate for packaging related PEPs for several years,
serving as the primary liaison between the CPython core development team and the
`Python Packaging Authority <https://www.pypa.io/>`__. Her own efforts in the
packaging space were focused primarily on the
`Python Packaging User Guide <https://packaging.python.org>`_ and facilitating
standardisation of interfaces between different tools to allow volunteers to
collaborate more effectively across a range of packaging projects.

At the PyCon US 2013 language summit, Alyssa successfully argued for updates to
the Python Enhancement Proposal process (described in PEP 1) that allowed
BDFL-Delegates to approve PEPs that don't affect the language definition or
the standard library directly on the relevant mailing lists (without needing
to rehash the discussions on python-dev).

She is now the project lead for the
`venvstacks <https://pypi.org/project/venvstacks/>`_ Python environment
packaging and deployment utility.

Beyond the Python open source world, Alyssa spent the first decade of her career
with Boeing Defence Australia working on high frequency radio communication for
the Australian Defence Force (including network contact and security protocols),
several years working on hardware integration test automation and other projects
for Red Hat and (most recently) several years with Tritium working to support
remote operation and management of Tritium's EV DC fast chargers using the Open
Charge Point Protocol (OCPP). Her work at Tritium included being a leading
member of the team that delivered 2020's world-first deployment of ISO15118's
Plug-and-Charge payment protocol support to Ionity's high power EV charging
network.

Alyssa is currently working for the `LM Studio <https://lmstudio.ai/>`_ team
maintaining ``venvstacks`` and working on other Python-related projects,
while also pursuing her Masters of Cybersecurity as a part-time student.


Selected articles, presentations and interviews
-----------------------------------------------

Selected Python Enhancement Proposals:

* PEP 338: `Executing modules as scripts <https://peps.python.org/pep-0338/>`__ (aka "the -m switch")
* PEP 343: `The "with" statement <https://peps.python.org/pep-0343/>`__ (co-authored with Guido van Rossum)
* PEP 366: `Main module explicit relative imports <https://peps.python.org/pep-0366/>`__
* PEP 394: `The "python" command on UNIX-like systems <https://peps.python.org/pep-0394/>`__ (co-authored with Kerrick Staley)
* PEP 414: `Explicit Unicode Literal for Python 3.3 <https://peps.python.org/pep-0414/>`__ (co-authored with Armin Ronacher)
* PEP 432 (superseded): `Simplifying the CPython interpreter startup sequence <https://peps.python.org/pep-0432/>`__
* PEP 440: `Version Identification and Dependency Specification <https://peps.python.org/pep-0440/>`__ (co-authored with Donald Stufft)
* PEP 453: `Bootstrapping pip in Python installations <https://peps.python.org/pep-0453/>`__ (co-authored with Donald Stufft)
* PEP 466: `Network Security Enhancements for Python 2.7.x <https://peps.python.org/pep-0466/>`__
* PEP 477: `Backport ensurepip to Python 2.7 <https://peps.python.org/pep-0477/>`__ (co-authored with Donald Stufft)
* PEP 489: `Multi-phase extension module initialisation <https://peps.python.org/pep-0489/>`__ (co-authored with Petr Viktorin and Stefan Behnel)
* PEP 493: `HTTPS verification migration tools for Python 2.7 <https://peps.python.org/pep-0493/>`__ (co-authored with Robert Kuska and Marc-Andre Lemburg)
* PEP 501 (superseded): `General purpose template literal strings <https://peps.python.org/pep-0501//>`__ (co-authored with Nick Humrich)
* PEP 538: `Coercing the legacy C locale to a UTF-8 based locale <https://peps.python.org/pep-0538/>`__
* PEP 565: `Show DeprecationWarning in __main__ <https://peps.python.org/pep-0565/>`__
* PEP 558 (superseded): `Defined semantics for locals() <https://peps.python.org/pep-0558/>`__
* PEP 573: `Module State Access from C Extension Methods <https://peps.python.org/pep-0573/>`__ (co-authored with Petr Viktorin, Eric Snow, and Marcel Plch)
* PEP 587: `Python Initialization Configuration <https://peps.python.org/pep-0587/>`__ (co-authored with Victor Stinner)
* PEP 628: `Add math.tau <https://peps.python.org/pep-0628/>`__


Selected Python related presentations (video links):

* Opportunities & Challenges in Open Collaboration

  * `PyCon Pune 2017 <https://pyvideo.org/pycon-pune-2017/keynote-opportunities-and-challenges-in-open-collaboration.html>`__

* Contributors, Colleagues, Clients & Customers: Sustaining Open Source Communities

  * `PyGotham 2015 keynote <https://pyvideo.org/pygotham-2015/contributors-colleagues-clients-customers-su.html>`__
  * `PyCon Poland 2015 keynote <https://pyvideo.org/pycon-pl-2015/contributors-colleagues-clients-customers-sustaining-open-source-communities.html>`__

* Python Beyond (C)Python (Adventures in Software Distribution):

  * `PyCon New Zealand 2014 keynote <https://pyvideo.org/video/3211/nick-coghlan-python-beyond-cpython-keynote>`__
  * `SciPy 2014 keynote <https://pyvideo.org/video/2785/python-beyond-cpython-adventures-in-software-dis>`__

* Python Packaging:

  * `Python Packaging 2.0: Playing Well With Others <https://www.youtube.com/watch?v=7An2GobbSWU>`__ (linux.conf.au 2014)
  * `Nobody Expects the Python Packaging Authority <https://pyvideo.org/video/2197/nobody-expects-the-python-packaging-authority>`__ (PyCon Australia 2013)

* CPython Core Development:

  * `Here be dragons: some elegant & ugly hacks in CPython <https://www.youtube.com/watch?v=VIBmWnlDjXc>`__ (PyCon Australia 2014)
  * `How Python Evolves <https://pyvideo.org/video/997/how-python-evolves-and-how-you-can-help-make-it>`__ (PyCon Australia 2011)

Selected Python related articles and presentation reviews:

* `Considering Python's target audience </posts/2017/10/considering-pythons-target-audience/>`__
* `The Python Packaging Ecosystem (September 2016) </posts/2016/09/python-packaging-ecosystem/>`__
* `27 Languages to Improve Your Python </posts/2015/10/languages-to-improve-your-python.html#broadening-our-horizons>`__
* `The Transition to Multilingual Programming <https://developers.redhat.com/blog/2014/09/09/transition-to-multilingual-programming-python/>`__
* `Why Python 4.0 won't be like Python 3.0 <https://developers.redhat.com/blog/2014/09/17/why-python-4-0-wont-be-like-python-3-0/>`__
* `Python 3 Q & A <https://python-notes.curiousefficiency.org/en/latest/python3/questions_and_answers.html>`__
* `Linux Weekly News article <https://lwn.net/Articles/580399/>`__ on my Python Packaging 2.0 presentation at linux.conf.au 2014
* `Justifying Python language changes </posts/2011/02/justifying-python-language-changes/>`__

Selected software design, development and deployment related presentations and articles:

* `Front-end Integration Testing with Splinter <https://pyvideo.org/pycon-au-2017/front-end-integration-testing-with-splinter.html>`__ (PyCon Australia 2017)
* `Tracking package updates with release-monitoring.org <https://lwn.net/Articles/711906/>`__ (LWN article on my linux.conf.au 2017 presentation)
* `What problem does it solve? </posts/2016/08/what-problem-does-it-solve/>`__ (on constructively criticising API designs)
* `Musings on the culture of python-dev </posts/2011/04/musings-on-culture-of-python-dev/>`__
* `Status quo wins a stalemate </posts/2011/02/status-quo-wins-stalemate/>`__
* `Scripting Languages and Suitable Complexity </posts/2011/08/scripting-languages-and-suitable/>`__
* `Path Dependent Development <https://pyvideo.org/video/1625/path-dependent-development-why-on-earth-are-you>`__ (PyCon Australia 2012)
* `Full Stack Integration Testing with Beaker <https://www.youtube.com/watch?v=tjUjdBm-Mqw>`__ (linux.conf.au 2014)

Selected community management related articles and interviews:

* `27 Languages to Improve Your Python (introduction) </posts/2015/10/languages-to-improve-your-python/>`__
* `The Quid Pro Quo of Open Infrastructure <https://community.redhat.com/blog/2015/02/the-quid-pro-quo-of-open-infrastructure/>`__
* `Abusing Contributors is not OK </posts/2015/01/abuse-is-not-ok/>`__ (reflecting on some comments from Linus Torvalds during his plenary session at linux.conf.au 2015)
* `Effective communication, brain hacking and diversity </posts/2011/07/effective-communication-brain-hacking/>`__
* `opensource.com interview <https://opensource.com/business/14/7/new-membership-process-python-software-foundation>`__ on my joining the PSF board of directors

Podcast appearances (in reverse chronological order):

* `Free as in Freedom <https://faif.us/cast/2015/mar/03/0x55/>`__ (with hosts Karen Sandler & Bradley M. Kuhn, recorded January 2015)
* `Pragmatic <https://techdistortion.com/podcasts/pragmatic/episode-35-written-by-kernel-hackers-for-kernel-hackers>`__ (with host John Chidgey, recorded August 2014)
* `From Python Import Podcast <https://frompythonimportpodcast.com/2014/03/31/episode-017-the-one-about-python-3/>`__ (with hosts Mike Pirnat & Dave Noyes and fellow guest Alex Gaynor, recorded March 2014)

  * Historical note of potential interest: I consider this discussion between Alex and myself to be one of the key events on the road to PEP 466's backport of Python 3 network security features to the Python 2.7 series, and PEP 476's switch to verifying HTTPS certificates by default in Python 2.7.9+ and 3.4.3+

* `Radio Free Python <https://radiofreepython.com/episodes/6/>`__ (with host Larry Hastings, recorded February 2012)
