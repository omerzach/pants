# Copyright 2014 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_tests(
  sources = ['test_linkify.py'],
  dependencies = [
    '3rdparty/python:future',
    'src/python/pants/reporting',
  ],
  timeout = 10,
)

python_tests(
  name = 'reporting_integration',
  sources = ['test_reporting_integration.py'],
  dependencies = [
    '3rdparty/python:future',
    '3rdparty/python:parameterized',
    'src/python/pants/util:contextutil',
    'tests/python/pants_test:int-test'
  ],
  tags = {'integration'},
  timeout = 240,
)
