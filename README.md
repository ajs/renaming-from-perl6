## Renaming Perl 6

External resources:
* [Original posting](https://www.reddit.com/r/perl6/comments/ctw5q3/consequences_for_perl_6_after_renaming)
* [The perl6/problem-solving PR](https://github.com/perl6/problem-solving/pull/89)

Technical coordination and planning around the Perl 6 renaming

This repository is a technical planning hub
for the _potential_ renaming of the Perl 6 programming
language. It's not the place to consider whether
such a renaming is desirable, but to track technical
and administrative issues.

The following project directories track each type of consequence and where
it may require changes:

* [domains](projects/domains)
* [ecosystem](projects/ecosystem)
* [forums-and-lists](projects/forums-and-lists)
* [language-documentation](projects/language-documentation)
* [language-general](projects/language-general)
* [language-specificaion](projects/language-specificaion)
* [moarvm](projects/moarvm)
* [nqp](projects/nqp)
* [perl5](projects/perl5)
* [projects](projects/projects)
* [rakudo](projects/rakudo)
* [third-party-documentation](projects/third-party-documentation)
* [third-party-software](projects/third-party-software)

And the original sketch of issues mapped to those projects is as follows:

* [Main Documentation text](projects/language-documentation/README.md)
* [Historical documentation: Synopses and Apocalypses](projects/language-documentation/README.md)
* [Error messages/any user-accessible strings](projects/rakudo/README.md)
* [Domain names](projects/domains/README.md)
* [Filename extensions (p6, t6, pm6)](projects/language-general/README.md)
* [`.perl`](projects/language-specificaion/README.md)
* [Installed compiler executable](projects/rakudo/README.md)
* [`use v6.x`](projects/language-specificaion/README.md)
* [`$*PERL`](projects/language-specificaion/README.md)
* [Editor syntax modes/plugins including markup/down](projects/third-party-software/README.md)
* [Wikipedia and other wikis](projects/third-party-documentation/README.md)
* [Reddit and other forums](projects/forums-and-lists/README.md)
* [Mailing lists](projects/forums-and-lists/README.md)
* [CPAN namespace for the Perl 6 ecosystem](projects/ecosystem/README.md)
* [Perl 5 "Perl6::..." Packages](projects/perl5/README.md)
* [All of the github projects whose names start with "Perl6-"](projects/projects/README.md)
* [NQP](projects/nqp/README.md)
* [Various internals (e.g. 6model)](projects/rakudo/README.md), ([also nqp](projects/nqp/README.md))

Okay, so for each item on the list, we need to decide:

* Can we enumerate exactly what falls into the item (for `.perl`, this is easy, for editor plugins, maybe not so much...)
* Do we need to change it? (Will it change organically if we don't?)
* If we change it, how will `<new-name>` be integrated? Can we know without knowing what the new name will be? Are there features of a new name that would make this easier/harder/impossible?
* If we change it, will (must?) the old naming remain for compatibility? For how long?
* Do third parties need to get involved? If so, whom?
* Are there administrative concerns? (e.g. making sure mods for a new subreddit are the same)
* Are there costs? Who will pay?
 
These will be broken down in individual documents
in this repository ...
