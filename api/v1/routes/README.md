#!/usr/bin/env python3

"""
infra-terraform README

This is a high-quality, production-ready Python package for managing infrastructure
as code with Terraform.
"""

from __future__ import print_function, division
from packaging import version

__version__ = '1.0.0'

try:
    import importlib_metadata
    __version__ = importlib_metadata.version('infra-terraform')
except ImportError:
    import pkg_resources
    __version__ = pkg_resources.get_distribution('infra-terraform').version