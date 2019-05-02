command to generate human-readable 20M randome txt files

	base64 /dev/urandom | head -c 20000000 > file<number>.txt
