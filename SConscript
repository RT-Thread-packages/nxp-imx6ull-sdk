import os
from building import *

objs = []
cwd  = GetCurrentDir()

if GetDepend(['SOC_MCIMX6X4']):
    objs = objs + SConscript('imx6ul-standard/SConscript')

if GetDepend(['SOC_IMX6ULL']):
    objs = objs + SConscript('imx6ul-smart/SConscript')


Return('objs')
