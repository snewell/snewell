Projects
========

biztonsag_
    A library designed to help with type safety when types would differ
    only by semantics (e.g., both :code:`Width` and :code:`Height` are
    numbers, but aren't interchangable).  Supports C++14 and later.

`dev-pipeline`_
    A tool to chain independent components into larger projects.  Largely
    inspired by some custom scripts I was using to handle deficencies of
    bundled dependencies (e.g., sub-modules and things like CMake's
    :code:`ExternalProject`).  The primary use case is projects where you
    may be developing libraries (that will be used in multiple products)
    at the same time you're developing code that consumes said libraries.

.. _biztonsag: https://github.com/snewell/biztonsag
.. _dev-pipeline: https://github.com/dev-pipeline
