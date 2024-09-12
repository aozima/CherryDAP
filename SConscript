from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c')
CPPPATH = [cwd]

src     += Glob('DAP/Source/*.c')
CPPPATH += [cwd + '/DAP/Include']

group = DefineGroup('CherryDAP', src, depend = [], CPPPATH = CPPPATH)

Return('group')
