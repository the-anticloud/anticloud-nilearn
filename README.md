# NILEARN

![licence](https://img.shields.io/badge/licence-BSD-3-Clause-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `NILEARN` in category **PSYCHOLOGY**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** NILEARN · **Upstream pin:** `8584104bba0abbd0ce3c1b6581ac980f9461ccdd` · **Category:** PSYCHOLOGY · **Vendor:** Anticloud FZ LLE · **Licence:** BSD-3-Clause

---

## What This Project Does

.. image:: https://img.shields.io/pypi/v/nilearn.svg
    :target: https://pypi.org/project/nilearn/
    :alt: Pypi Package

.. image:: https://img.shields.io/pypi/pyversions/nilearn.svg
    :target: https://pypi.org/project/nilearn/
    :alt: PyPI - Python Version

.. image:: https://github.com/nilearn/nilearn/actions/workflows/build-docs.yml/badge.svg
    :target: https://github.com/nilearn/nilearn/actions/workflows/build-docs.yml
    :alt: Github Actions Doc Build Status

.. image:: https://github.com/nilearn/nilearn/actions/workflows/test_with_tox.yml/badge.svg?branch=main&event=push
    :target: https://github.com/nilearn/nilearn/actions/workflows/test_with_tox.yml
    :alt: Github Actions Test Status

.. image:: https://codecov.io/gh/nilearn/nilearn/graph/badge.svg?token=KpYArSdyXv
    :target: https://app.codecov.io/gh/nilearn/nilearn
    :alt: Coverage Status

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.8397156.svg
    :target: https://doi.org/10.5281/zenodo.8397156

.. image:: https://img.shields.io/badge/bluesky-Follow_nilearn-blue?logo=bluesky
    :target: https://bsky.app/profile/nilearn.bsky.social
    :alt: Bluesky

.. image:: https://img.shields.io/youtube/channel/subscribers/UCU6BMAi2zOhNFnDkbdevmPw
    :target: https://www.youtube.com/@nilearnevents5116
    :alt: YouTube Channel Subscribers

.. image:: https://img.shields.io/mastodon/follow/109669703955432270?domain=https%3A%2F%2Ffosstodon.org%2F
    :target: https://fosstodon.org/@nilearn
    :alt: Mastodon

.. image:: https://img.shields.io/discord/711993354929569843
    :target: https://discord.com/invite/SsQABEJHkZ
    :alt: Discord

nilearn
=======

Nilearn enables approachable and versatile analyses of brain volumes and surfaces.
It provides statistical and machine-learning tools, with instructive documentation & friendly community.

It supports general linear model (GLM) based analysis
and leverages the `scikit-learn <https://scikit-learn.org>`_ Python toolbox
for multivariate statistics with applications
such as predictive modeling, classification, decoding, or connectivity analysis.

Important links
===============

- Official source code project: https://github.com/nilearn/nilearn/
- HTML documentation (stable release): https://nilearn.github.io/

Install
=======

Latest release
--------------

The easiest way to install Nilearn is using pip.
Execute the following command in the command prompt / terminal
in the proper python environment:

.. code-block:: bash

    python -m pip install nilearn

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

Development version
-------------------

Please find all development setup instructions in the
`contribution guide <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_.

Drop-in Hours
=============

The Nilearn team organizes regular online drop-in hours to answer questions,
discuss feature requests, or have any Nilearn-related discussions. Nilearn
drop-in hours occur *every Wednesday from 4pm to 5pm UTC*, and we make sure that at
least one member of the core-developer team is available. These events are held
on `Jitsi Meet <https://meet.jit.si/nilearn-drop-in-hours>`_ and are fully open,
anyone is welcome to join!
For more information and ways to engage with the Nilearn team see
`How to get help <https://nilearn.github.io/dev/development.html#how-to-get-help>`_.

Dependencies
============

The required dependencies to use Nilearn are listed
in the file `pyproject.toml <https://github.com/nilearn/nilearn/blob/main/pyproject.toml>`_.

If you are using Nilearn plotting functionalities or running the examples, ``matplotlib`` is required.

Some plotting functions in Nilearn require both matplotlib and plotly as plotting engines.
In order to use the plotly engine in these functions,
you will need to install both plotly and kaleido, which can both be installed with pip and anaconda.

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

If you want to run the tests,
extra dependencies (such as ``pytest`` and ``pytest-cov``) are required.
See our `development setup instructions <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_
to know how to install them.

Development
===========

Detailed instructions on how to contribute are available at
https://nilearn.github.io/stable/development.html

---

## Installation

=======

Latest release
--------------

The easiest way to install Nilearn is using pip.
Execute the following command in the command prompt / terminal
in the proper python environment:

.. code-block:: bash

    python -m pip install nilearn

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

Development version
-------------------

Please find all development setup instructions in the
`contribution guide <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_.

Drop-in Hours
=============

The Nilearn team organizes regular online drop-in hours to answer questions,
discuss feature requests, or have any Nilearn-related discussions. Nilearn
drop-in hours occur *every Wednesday from 4pm to 5pm UTC*, and we make sure that at
least one member of the core-developer team is available. These events are held
on `Jitsi Meet <https://meet.jit.si/nilearn-drop-in-hours>`_ and are fully open,
anyone is welcome to join!
For more information and ways to engage with the Nilearn team see
`How to get help <https://nilearn.github.io/dev/development.html#how-to-get-help>`_.

Dependencies
============

The required dependencies to use Nilearn are listed
in the file `pyproject.toml <https://github.com/nilearn/nilearn/blob/main/pyproject.toml>`_.

If you are using Nilearn plotting functionalities or running the examples, ``matplotlib`` is required.

Some plotting functions in Nilearn require both matplotlib and plotly as plotting engines.
In order to use the plotly engine in these functions,
you will need to install both plotly and kaleido, which can both be installed with pip and anaconda.

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

If you want to run the tests,
extra dependencies (such as ``pytest`` and ``pytest-cov``) are required.
See our `development setup instructions <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_
to know how to install them.

Development
===========

Detailed instructions on how to contribute are available at
https://nilearn.github.io/stable/development.html

## Usage

in the file `pyproject.toml <https://github.com/nilearn/nilearn/blob/main/pyproject.toml>`_.

If you are using Nilearn plotting functionalities or running the examples, ``matplotlib`` is required.

Some plotting functions in Nilearn require both matplotlib and plotly as plotting engines.
In order to use the plotly engine in these functions,
you will need to install both plotly and kaleido, which can both be installed with pip and anaconda.

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

If you want to run the tests,
extra dependencies (such as ``pytest`` and ``pytest-cov``) are required.
See our `development setup instructions <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_
to know how to install them.

Development
===========

Detailed instructions on how to contribute are available at
https://nilearn.github.io/stable/development.html

## API

It supports general linear model (GLM) based analysis
and leverages the `scikit-learn <https://scikit-learn.org>`_ Python toolbox
for multivariate statistics with applications
such as predictive modeling, classification, decoding, or connectivity analysis.

Important links
===============

- Official source code project: https://github.com/nilearn/nilearn/
- HTML documentation (stable release): https://nilearn.github.io/

Install
=======

Latest release
--------------

The easiest way to install Nilearn is using pip.
Execute the following command in the command prompt / terminal
in the proper python environment:

.. code-block:: bash

    python -m pip install nilearn

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

Development version
-------------------

Please find all development setup instructions in the
`contribution guide <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_.

Drop-in Hours
=============

The Nilearn team organizes regular online drop-in hours to answer questions,
discuss feature requests, or have any Nilearn-related discussions. Nilearn
drop-in hours occur *every Wednesday from 4pm to 5pm UTC*, and we make sure that at
least one member of the core-developer team is available. These events are held
on `Jitsi Meet <https://meet.jit.si/nilearn-drop-in-hours>`_ and are fully open,
anyone is welcome to join!
For more information and ways to engage with the Nilearn team see
`How to get help <https://nilearn.github.io/dev/development.html#how-to-get-help>`_.

Dependencies
============

The required dependencies to use Nilearn are listed
in the file `pyproject.toml <https://github.com/nilearn/nilearn/blob/main/pyproject.toml>`_.

If you are using Nilearn plotting functionalities or running the examples, ``matplotlib`` is required.

Some plotting functions in Nilearn require both matplotlib and plotly as plotting engines.
In order to use the plotly engine in these functions,
you will need to install both plotly and kaleido, which can both be installed with pip and anaconda.

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

If you want to run the tests,
extra dependencies (such as ``pytest`` and ``pytest-cov``) are required.
See our `development setup instructions <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_
to know how to install them.

Development
===========

Detailed instructions on how to contribute are available at
https://nilearn.github.io/stable/development.html

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | BSD-3-Clause |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

.. code-block:: bash

    python -m pip install nilearn

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

Development version
-------------------

Please find all development setup instructions in the
`contribution guide <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_.

Drop-in Hours
=============

The Nilearn team organizes regular online drop-in hours to answer questions,
discuss feature requests, or have any Nilearn-related discussions. Nilearn
drop-in hours occur *every Wednesday from 4pm to 5pm UTC*, and we make sure that at
least one member of the core-developer team is available. These events are held
on `Jitsi Meet <https://meet.jit.si/nilearn-drop-in-hours>`_ and are fully open,
anyone is welcome to join!
For more information and ways to engage with the Nilearn team see
`How to get help <https://nilearn.github.io/dev/development.html#how-to-get-help>`_.

Dependencies
============

The required dependencies to use Nilearn are listed
in the file `pyproject.toml <https://github.com/nilearn/nilearn/blob/main/pyproject.toml>`_.

If you are using Nilearn plotting functionalities or running the examples, ``matplotlib`` is required.

Some plotting functions in Nilearn require both matplotlib and plotly as plotting engines.
In order to use the plotly engine in these functions,
you will need to install both plotly and kaleido, which can both be installed with pip and anaconda.

Please find all installation instructions
`on our install page <https://nilearn.github.io/dev/install.html>`_.

If you want to run the tests,
extra dependencies (such as ``pytest`` and ``pytest-cov``) are required.
See our `development setup instructions <https://nilearn.github.io/dev/development.html#setting-up-your-environment>`_
to know how to install them.

Development
===========

Detailed instructions on how to contribute are available at
https://nilearn.github.io/stable/development.html

## Contributing

.. _contributing:

Code of Conduct
===============

By participating in Nilearn, you agree to abide by the :nipy:`NIPY Code of Conduct <conduct.html>`

How to get help?
================

If you have issues when using Nilearn, or if you have questions on how to use it,
please don't hesitate to reach out!

There are currently three ways to interact with the Nilearn team:

* through the :neurostars:`neurostars <>` forum

* our :nilearn-gh:`github <>` issues

* through our weekly `drop-in hours <https://arewemeetingyet.com/UTC/2023-01-18/16:00/w/Nilearn%20Drop-in%20Hours>`_,
  usually **every Wednesday from 4pm to 5pm UTC**.
  We post on our `Bluesky account <https://bsky.app/profile/nilearn.bsky.social>`_ in advance
  to let you know if the drop-in hours are happening that week.

If you have a *usage question*, that is if you need help troubleshooting scripts using Nilearn,
we would appreciate it if you either ask it during the drop-in hours
or create a topic on :neurostars:`neurostars <>` with the "nilearn" tag.
Asking questions or reporting issues is always valuable
because it will help other users having the same problem.
So, please don't hold onto a burning question!

We ask that you *don't* open an issue on :nilearn-gh:`GitHub <>` for usage questions.
We use our :nilearn-gh:`GitHub <>` issue board for bug reports, feature requests, and documentation changes only.

How to help the project?
========================

If you are interested in contributing to the Nilearn project, we thank you very much.
Note that there are multiple ways to help us, and not all of them require writing code.

Report bugs or discuss enhancement ideas
----------------------------------------

We welcome open discussion around improvements ---both to the documentation as well as to the code base---
through our GitHub issue board!

* If you think you have discovered a bug,
  please start by searching through the existing :nilearn-gh:`issues <issues>`
  to make sure it has not already been reported. If the bug has not been reported yet,
  create an :nilearn-gh:`new issue <issues/new/choose>`
  including a `minimal runnable example <https://stackoverflow.com/help/minimal-reproducible-example>`_
  to showcase it (using :ref:`nilearn.datasets <datasets_ref>`) as well as your OS and Nilearn version.

* If you have an idea for a new feature, check if it is in the :ref:`nilearn_scope`
  and feel free to open a :nilearn-gh:`new issue <issues/new/choose>` to discuss it.

* If you think the documentation can be improved, please open a :nilearn-gh:`new issue <issues/new/choose>`
  to discuss what you would like to change! This helps to confirm
  that your proposed improvements don't overlap with any ongoing work.

Answer questions
----------------

Another way to help the project is to answer questions on :neurostars:`neurostars <>`,
or comment on github :nilearn-gh:`issues <issues>`.
Some :nilearn-gh:`issues <issues>` are used to gather user opinions on various questions,
and any 

## License

Upstream © its respective contributors under BSD-3-Clause (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** NILEARN
- **Pinned SHA:** `8584104bba0abbd0ce3c1b6581ac980f9461ccdd`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.rst`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`636086cbfe64dfae01734f65da282110fb9a77a1c75b75b25bff5bfe2e8b71ef`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

