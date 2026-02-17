# Python-program-to-strip-a-set-of-characters-from-a-string.
def strip_chars(str, chars):
return &quot;&quot;.join(c for c in str if c not in chars)
print(&quot;\nOriginal String: &quot;)
print(&quot;The quick brown fox jumps over the lazy dog.&quot;)
print(&quot;After stripping a,e,i,o,u&quot;)
print(strip_chars(&quot;The quick brown fox jumps over the lazy dog.&quot;, &quot;aeiou&quot;))
print()
