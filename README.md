Rundown
=======

If you're here, then I'm sure you know what de4dot is. If you don't, see the [original de4dot's README.md](https://github.com/de4dot/de4dot#readme) for details. 

We will be using [congviet's dnlib](https://github.com/congviet/dnlib) rather than the original, and retargeting it to .NET 5.0 (if it isn't already; I haven't checked).



Plans
=====

- Retarget the .NET v3.5 and v4.5 branch to v4.8, and add a few tweaks and updates. This branch will not receive future updates, tweaks, customizations or support after the migration is complete. Bug fixes are welcome if you make them yourself and submit a pull request.
- Create a new master branch targeting .NET Framework v5.0 that will recieve feature updates, fixes, and tweaks, but no support. Bug fixes are welcome if you make them yourself and submit a pull request, or if I notice them myself and go to fix it.
- Updating CryptoObfuscator option to support v7, since it uses one class to decrypt strings and several classes to decrypt constants from the embedded resource file, rather than a single method that handles everything. This will be an advanced option, and I have no plans to make it automatically detect v7. It is always a good idea to do your own recon on your target program first. This option, co2, will have an auto-detect-methods option, as well as a manual-token-set option that takes arguments for the method tokens. The manual tokens are ALWAYS the better option assuming you've correctly assigned them.

Progress
========
Absolutely nothing, yet.
