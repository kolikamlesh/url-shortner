# myUrl
input any long url it will return short url in formate 'localhost:9000/resolve/xxxxxx'
this url is comparatively small to the given input and shared ifficiently among users
xxxxxxx this is 7 or more character long id according to the url 

it is md5 hash generated by system if any collision happens then it appends a serial number at last of id
e.g.

abcdefg
abcdefg1
abcdefg2
abcdefg3
.
.
.

and so on thats why we always have an id for every url
in this app there are two options provided redirect and copy by using them you can redirect or copy the url

___________________________________________________________________

# md5

The MD5 (Message Digest Algorithm 5) is a widely used cryptographic hash function that takes an input (message) and produces a 128-bit hash value, typically represented as a 32-character hexadecimal number. The output of the MD5 algorithm is not directly related to any specific characters but is derived from binary data.

The 32-character hexadecimal representation of the MD5 hash is composed of the digits 0-9 and the letters A-F (uppercase). Each character represents 4 bits, allowing for a total of 16 possible values (0-15) per character.

Therefore, the characters used in the MD5 hash representation are:

Digits: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
Letters (uppercase): A, B, C, D, E, F
Example MD5 hash: 5D41402ABC4B2A76B9719D911017C592

In the example above, each character in the MD5 hash is one of the characters listed.
___________________________________________________________________

for 7 charater there are ( 15 x 15 x 15 x 15 x 15 x 15 x 15 ) + n possibilities of unique urls with collision resolving technique we can generate enumorous amount
of urls 

here 'n' is number of collisions occured for specific id
