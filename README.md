# VCV Rack Manual

The scope of the manual is the VCV Rack application. It does not include individual plugins for Rack---those should be documented and hosted by the plugin developer.

## Contributions

Send a pull request to this repository with your edits.
Major changes like new pages and complete overhauls are welcome, as well as minor fixes like grammar, spelling, and reorganization.
Your PR will be accepted if it is a net positive benefit to readers.

## Building

Install [Sphinx](http://www.sphinx-doc.org/en/stable/) 1.8.1. Newer versions do not generate formulas and image tags properly.

	pip install sphinx==1.8.1
	pip install sphinx_rtd_theme

Install [recommonmark](https://github.com/rtfd/recommonmark) 0.4.0.

	pip install recommonmark==0.4.0

Build with

	make html

The output should be generated in `_build/html`.

## License

All documentation text in this repository is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Images such as screenshots and logos are licensed by their respective owner.
