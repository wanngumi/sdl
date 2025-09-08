env = Environment(tools = ['mingw'])
env['ENV']['PATH'] = ['C:/wanngumi/TDM-GCC-64/bin']

# env.Append(CPPPATH = ['../SDLdeps/include'])
# env.Append(LIBPATH = ['../SDLdeps/lib'])

env.Append(LINKFLAGS = ['-static'])
# env.Append(LIBS = ['SDL3', 'm', 'kernel32', 'user32', 'gdi32', 'winmm', 'imm32', 'ole32', 'oleaut32', 'version', 'uuid', 'advapi32', 'setupapi', 'shell32', 'dinput8'])
env.Append(LIBS = ['SDL3', 'ssp', 'winmm', 'ole32', 'setupapi', 'gdi32', 'imm32', 'version', 'oleaut32', 'uuid'])

env.Program('snake.c')
