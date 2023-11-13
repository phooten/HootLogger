# Messages Package

This is a package that can be included in projects to output messages

Example logging REPO: https://github.com/srtamrakar/python-logger/tree/master


# Installation tips:

<pip install .>

installs:
    tar under the 'dist'
    creates .egg-info

Needed files:
    setup.py
    LICEANSE
    README


Layouts:
    flat-layouts:

    src-layout:



Questions:
    setup.cfg:
        

    setup.py:
        Instructions to build software. Maybe some configuration options like computing test coverage or unit tests or
        the install prefix.

    pyproject.toml:
        Specifies the project's metadata.
        Used to replace .cfg, but formats everything in TOML. ( Tom's Obvious, Minimal Language: https://en.wikipedia.org/wiki/TOML )
        You can put "Abstract Dependancies" here, but not pinned dependencies. Pinned ones belong in the requirements.txt

    requirements.txt:
        Not the same thing as setup.cfg. Needed for a different reason. This is typically used for deploymnet with
        version pinned dependencies. The reason is so you don't get the latest and greatest, and only get the version
        you know you have explicitley tested.
