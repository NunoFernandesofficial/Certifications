
What are indicators?

	Indicators of compromise aka IOC´s are a method of information sharing, so that organisations can determine whether they have come into contact with similar attacks. 
	
	Here are some examples of IOC´s:
	IP Addresses: If an IP is behaving maliciously it can be considered an IOC
	Email addresses: If an email is sending out malicious emails, it can be considered an IOC
	File sizes value: It´s pretty unlikely that a large number of files will have the exact same number of bytes.
	MD5/SHA-1 Hashes: Hashing is a one-way cryptographic function that allows us to create a signature represented by a string value, known as a checksum.
	Strings: We can retrieve strings from a file, and use them as an IOC for searching (using strings command).


Fyle property indicatos:

	Retrieving file size property:
		Right-click > properties > size value
		ls -lh (command linux)

	Retrieving file name property:
		Right-click > properties > name value
		ls (command linux)

File hash indicators:

	What are hashes?
		a hash is a unique string value that corresponds to the contents of the file. They are generated by hashing algorithms, such as MD5 or SHA256, if two files are exactly the same, the hash will match.

	Generating a MD5 checksum:
		md5sum file.txt
	Generating a sha256 checksum:
		sha256sum file.txt
	Powershell to get hash:
		Get-FileHash file.txt -algorithm MD5/SHA1
	