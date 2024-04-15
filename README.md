# bt-nslookup

Tool for name server look up on IP address list

## usage 
`
	kali@kali:bt-nslookup> ./bt-nslookup -h
	Usage: /usr/local/bin/bt-nslookup -f <target_file> -o <output_file> [-t <max_threads>]
	Options:
	  -f <target_file>       File containing target list
	  -o <output_file>       Output file to save results
	  -t <max_threads>       Maximum number of threads (default: 40, max: 100)
	  -h                      Display this help message
`
You can use grep to get your specific target
`
	cat output.txt | grep example.com
	cat output.txt | grep -E "example.com|nmap.org"
`