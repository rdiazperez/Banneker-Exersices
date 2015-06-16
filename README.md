#!/usr/bin/env python
# Banneker-Exersices
import numpy as np
import sys

if sys.argv[0] > sys.argv[1]:
  for i in range(len(sys.argv)):
    sys.argv[i] % sys.argv[0]  = 0
    print(sys.argv[i] * sys.argv[0])
  if sys.argv[i] % sys.argv[0] != 0:
    print(sys.argv[i])
    print(sys.argv[0]*sys.argv[i])
