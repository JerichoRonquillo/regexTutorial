<strong>Regex Tutorial</strong>

Here is what I've learned about regex.

<strong>Summary</strong>
Regular expressions are extremely useful in extracting information
from any text by searching for one or more matches of a specific search pattern 

Example: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

<strong>Anchors</strong>
The Anchors are found at the beginning and end of the string and they are used to specify the location within a string to search.


<strong>Quantifiers</strong>
Quantifiers lets you specify the number of times you want a regex string to match. They can be either a lazy or greedy variant. 
Lazy quantifies allow a limit matching and can also include other 
limiting characters to specify how many times a match is found.


^   Match at the beginning of the line
$   Match at the end of a line


* and *? Match zero or more times.
+ and +? Match one or more times.
? and ?? Match zero or one time.
{n} and {n}? Match exactly n times.
{n,} and {n,}? Match at least n times.
{n,m} and {n.m}? Match from n to me times.

<bold>Grouping Constructs</bold>
Grouping allows you to find specific information from a given group to keep info organized by using paranthesis '()'.

(https?:\/\/)   A grouping consisting of 'https://', 'http://' or none.
([\/\w \.-]*)   This grouping includes '*' which allows for as many matches needed like multiple directories.


<strong>Bracket Expressions</strong>

<strong>Character Classes</strong>
Also known as a "character set" lets you tell the regex engine to match a single character. 
The main one seen in the regex string is \d which matches for any single digit. Another one that can be seen is 
\wwhich matches word characters. Both these examples can be seen in these bracket expressions:

[\da-z\.-]
[\/\w \.-]


<strong>Character Escapes</strong>
Escaped characters are symbolized by the use of a backslash \. You can escape letters 
that represent common character class like 
\w for word character as seen in the previous section.

<strong>Regex Tutorial</strong>

Here is what I've learned about regex.

<strong>Summary</strong>
Regular expressions are extremely useful in extracting information
from any text by searching for one or more matches of a specific search pattern 

Example: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

<strong>Anchors</strong>
The Anchors are found at the beginning and end of the string and they are used to specify the location within a string to search.


<strong>Quantifiers</strong>
Quantifiers lets you specify the number of times you want a regex string to match. They can be either a lazy or greedy variant. 
Lazy quantifies allow a limit matching and can also include other 
limiting characters to specify how many times a match is found.


^   Match at the beginning of the line
$   Match at the end of a line


* and *? Match zero or more times.
+ and +? Match one or more times.
? and ?? Match zero or one time.
{n} and {n}? Match exactly n times.
{n,} and {n,}? Match at least n times.
{n,m} and {n.m}? Match from n to me times.

<bold>Grouping Constructs</bold>
Grouping allows you to find specific information from a given group to keep info organized by using paranthesis '()'.

(https?:\/\/)   A grouping consisting of 'https://', 'http://' or none.
([\/\w \.-]*)   This grouping includes '*' which allows for as many matches needed like multiple directories.


<strong>Bracket Expressions</strong>

<strong>Character Classes</strong>
Also known as a "character set" lets you tell the regex engine to match a single character. 
The main one seen in the regex string is \d which matches for any single digit. Another one that can be seen is 
\wwhich matches word characters. Both these examples can be seen in these bracket expressions:

[\da-z\.-]
[\/\w \.-]


<strong>Character Escapes</strong>
Escaped characters are symbolized by the use of a backslash \. You can escape letters 
that represent common character class like 
\w for word character as seen in the previous section.

[\/\w \.-]