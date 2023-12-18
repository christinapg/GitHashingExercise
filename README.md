The Bash hash script is a concise utility designed to generate a SHA-256 hash from a 4-digit integer.
The script, implemented in Bash, takes a 4-digit integer as a command-line argument and checks for the correct input format.
It ensures that the provided argument is a valid 4-digit integer, displaying a usage message and exiting with an error if the input is incorrect.
Upon successful validation, the script proceeds to compute the SHA-256 hash of the input using the sha256sum command.
The resulting hash is then displayed.
The hash_output.txt file contains the output of the script for the unique integer 0583.
The input unique 4-digit-integer comes from the the last four digits of my student ID (10583).
Usage:
./hash_script <4-digit-integer>

