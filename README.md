# Authorization Pip and Conda Behind The Corporate Firewall

This repository includes web addresses that should be whitelisted to be able to install python and conda packages on the corporate firewall.

## Abstract

When I was working in a corporate company, we have faced an issue. Internet access was not allowed for production servers. The network team was only allowed to open internet access for indicated web addresses because of the cybersecurity rules. Web addresses were filtered from the internet, to be able to install packages using pip and conda. I will share a list of these web URL's below.

## Web URI List

```text
https://pypi.python.org
https://pypi.org
https://pythonhosted.org
https://files.pythonhosted.org/
https://conda.binstar.org/numba/win-64/
https://conda.anaconda.org/
https://binstar.org/
https://anaconda.org/
https://repo.continuum.io/
https://pypi.python.org/
```

## References

* [https://stackoverflow.com/questions/14277088/what-url-should-i-authorize-to-use-pip-behind-a-firewall](https://stackoverflow.com/questions/14277088/what-url-should-i-authorize-to-use-pip-behind-a-firewall)
* [https://stackoverflow.com/questions/33778507/unable-to-update-conda-packages-behind-corporate-firewall-updated-condarc-file](https://stackoverflow.com/questions/33778507/unable-to-update-conda-packages-behind-corporate-firewall-updated-condarc-file)
* [https://packaging.python.org/glossary/\#term-Python-Package-Index-PyPI](https://packaging.python.org/glossary/#term-Python-Package-Index-PyPI)
* [https://en.wikipedia.org/wiki/Pip\_\(package\_manager\)](https://en.wikipedia.org/wiki/Pip_%28package_manager%29)

