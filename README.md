# pwdgen
A simple script to create random passwords on Linux. It has no tricks. It's simple. You can read the code easily!


# How setup it?

## Where I can allocate it?

You'll set up this script at your system just copying it to your favorite directory. I suggest to allocate it at `/usr/local/bin` to keep your filesystem organized.

## Execution Permission

Now you need to set up execution permission. You probably already chose a cool name. I'll use the name `pwdgen`:

`chmod +x /usr/local/bin/pwdgen`

This is it!

# How to run?

If you used a path that is included at $PATH environment variable, you can run `pwdgen` or another name that you choose. Otherwise, you'll need to run that script using the absolute path like this; `/path/to/my/script`.

First, you need to inform the type of password you wish (alphanumeric or with special characters) and the password size (eg: 10 characters).

Five options of passwords will be informed.

```w1l@mandragora:~> pwdgen 

[1] Alphanumeric.
[2] With special characters.

< Inform your choice: 1
< Password size: 15

OCK5hTEUtQGBghj
ltGtyiaxNKrazyf
b1DW7CEbfCsUiKA
VZks9YKj7i1d4Ez
FPc8sPMFDwymriR```
