Import('*')

INC = [ '#/vm/inc', '#/peripherals/simple_kb', '#/peripherals/simple_term' ]

LIBS = [ 'libminiat', 'libsimple_kb', 'libsimple_term' ]

buildProgram("miniat_console", "console.c", CPPPATH=INC, LIBS=LIBS)
buildProgram("miniat_console_connector", "console_connector.c", CPPPATH=INC, LIBS=LIBS)
buildProgram("crush", "crush.c", CPPPATH=INC, LIBS=LIBS)
