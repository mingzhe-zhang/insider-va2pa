Import('*')

Command('lib/test-rename.c', 'lib/insider.c', Move('$TARGET', '$SOURCE'))
AddSource('insider-test.c')
AddSource('lib/test-rename.c')
