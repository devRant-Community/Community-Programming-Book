# Advantages

Perl derives most of its syntax from well known languages and tools common in UNIX-like operating systems.

Becoming good programmer with Perl, with previous knowledge of C, Shell script, Sed, Awk and other UNIX tools
is relatively easy. Perl is **really** easy to learn!

Perl is a very entraining language to work (like C or Assembly) because of freedom it provides. The language has
bad reputation because of the "write only" way code can be produced in it, but, to be honest, you can write obfuscated
code in all languages, some make it more difficult (Assembly, Java), some make it less difficult (JavaScript, Perl).
//TODO: Move to disadvantages :)

Perl with CPAN, has a module to do pretty much anything you'd ever want to do and even more for things you
probably don't want to do.

Perl is stable and predictable - it just requires basic UNIX knowledge and decent Perl intuition.

Finally, Perl has developed text processing capabilities to the extreme - You want to strip newlines from input? Check it out:

```pl
$_ = do { local $/; <> };
s/[\n\r\t ]+//g;
print;
```

As you can see, it's pretty simple and compact!
