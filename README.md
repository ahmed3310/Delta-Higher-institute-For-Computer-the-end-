# @@ -1,9 +1,16 @@
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

import sys

try:
    raw_input  # Python 2
    sys.exit('Please use Python 3 to run Wifiphisher.')
except NameError:
    pass  # Python 3

import logging
import os
import sys

from wifiphisher.pywifiphisher import run