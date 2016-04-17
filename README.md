# base64Image
Base64 Image Manipulation

Most modern desktop browsers such as Chrome, Mozilla, Internet Explorer supports images encoded as data url

you can embed data url based on Base64 format into html tag 

From http://en.wikipedia.org/wiki/Base64

The term Base64 refers to a specific MIME content transfer encoding. It is also used as a generic term for any similar encoding scheme that encodes binary data by treating it numerically and translating it into a base 64 representation. The particular choice of base is due to the history of character set encoding: one can choose a set of 64 characters that is both part of the subset common to most encodings, and also printable. This combination leaves the data unlikely to be modified in transit through systems, such as email, which were traditionally not 8-bit clean.

Base64 can be used in a variety of contexts:

Evolution and Thunderbird use Base64 to obfuscate e-mail passwords[1]
Base64 can be used to transmit and store text that might otherwise cause delimiter collision
Base64 is often used as a quick but insecure shortcut to obscure secrets without incurring the overhead of cryptographic key management
Spammers use Base64 to evade basic anti-spamming tools, which often do not decode Base64 and therefore cannot detect keywords in encoded messages.
Base64 is used to encode character strings in LDIF files
Base64 is sometimes used to embed binary data in an XML file, using a syntax similar to ...... e.g. Firefox's bookmarks.html.
Base64 is also used when communicating with government Fiscal Signature printing devices (usually, over serial or parallel ports) to minimize the delay when transferring receipt characters for signing.
Base64 is used to encode binary files such as images within scripts, to avoid depending on external files.
Can be used to embed raw image data into a CSS property such as background-image.

try to convert your Images using this tools : 
http://www.dailycoding.com/Utils/Converter/ImageToBase64.aspx

copy the data uri and embed in image html tags

demo : 
https://jsfiddle.net/shiddiq/zq7abqxc/
