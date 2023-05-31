Python Modules Links
====================

This directory contains links to the Python modules of plugins and XBlocks used in edx-platform.

This is mostly used to enable ``atlas`` fetch translations by module name rather than by repository name for two reasons:

1. In Python runtime, repo names are not available, but module names are.
2. Repo names can change but module names don't.

The links in this file are created by the ``extract-translation-source-files.yml`` GitHub Action workflow in this repo.
