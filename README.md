sf-parsers
==========

Parsers used to convert the text files in HackNightBulkData to the StateDecoded XML files

1. `export PYTHONIOENCODING='UTF-8'`
2. `./parseCode.py -i <Hack Night File> -x <XML Directory> > out.txt 2>&1`
3. (Optional convenience script for runnin on all codes)
	`./scripts/runParser.py > out.txt 2>&1`
