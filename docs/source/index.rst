.. BEAM VM Wisdoms documentation master file

Welcome, adventurer!
====================

This is the collection of easy to read (ELI5) articles as well as in-depth
knowledge such as VM internals, memory layout, opcodes etc.
The project is work in progress, so come back soon!
Github repository for pages https://github.com/kvakvs/beam-wisdoms

Latest
``````

*   2017-03-17  Data copying ELI5, efficiency guide
*   2017-01-21  updated hints about ``StrT`` BEAM section and fixed Github links
                to ``gluonvm`` which is now deprecated and renamed to ``gluonvm1``.
*   2016-10-17  :doc:`eli5-io` (upd.), :doc:`indepth-io`

ELI5 Section (Explain Me Like I'm Five)
---------------------------------------

.. toctree::
    :maxdepth: 1

    eli5-vm
    eli5-atoms
    eli5-processes
    eli5-process-heap
    eli5-io
    eli5-tracing
    eli5-bif-nif
    eli5-types
    eli5-etf
    eli5-property-based
    eli5-efficiency


Deeper Knowledge Section
------------------------

.. toctree::
    :maxdepth: 2

    definitions
    indepth-memory-layout
    indepth-data-sizes
    indepth-heap-layout
    interfacing
    indepth-beam-file
    indepth-beam-instructions
    indepth-io

.. todo::
    More details from ELI5 articles;
    IO and ports;
    Links and monitors;
    ETS?;
    BIFs, traps;
    Process: Exceptions;
    Ext term format

Smaller things you would've never noticed otherwise. OTP C source-related.

:doc:`otp-c-style-guide`, :doc:`otp-cpp-ramblings`, :doc:`otp-c-refactor-todo`
