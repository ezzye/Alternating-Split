

# Alternating-Split
Simple Encryption #1

For building the encrypted string:
Take every 2nd char from the string, then the other chars, that are not every 2nd char, and concat them as new String.
Do this n times!

Examples:

"This is a test!", 1 -> "hsi  etTi sats!"
"This is a test!", 2 -> "hsi  etTi sats!" -> "s eT ashi tist!"
Write two methods:

String encrypt(final String text, final int n)
String decrypt(final String encryptedText, final int n)
For both methods:
If the input-string is null or empty return exactly this value!
If n is <= 0 then return the input text.

Use https://maven.apache.org/guides/getting-started/index.html for maven

mvn -B archetype:generate \
  -DarchetypeGroupId=org.apache.maven.archetypes \
  -DgroupId=com.itshackney.app \
  -DartifactId=alternatingSplit
