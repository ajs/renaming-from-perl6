## Remaining Perl 6

[Original posting](https://www.reddit.com/r/perl6/comments/ctw5q3/consequences_for_perl_6_after_renaming)

Technical coordination and planning around the Perl 6 renaming

This repository is a technical planning hub
for the _potential_ renaming of the Perl 6 programming
language. It's not the place to consider whether
such a renaming is desirable, but to track technical
and administrative issues.

The list of things that have Perl 6 naming and ***may*** have to change:

* Main Documentation text
* Historical documentation: Synopses and Apocalypses
* Error messages/any user-accessible strings
* Domain names
* Filename extensions (p6, t6, pm6)
* `.perl`
* Installed compiler executable
* `use v6.x`
* `$*PERL`
* Editor syntax modes/plugins including markup/down
* Wikipedia and other wikis
* Reddit and other forums (oh hai!)
* Mailing lists
* CPAN namespace for the Perl 6 ecosystem
* Perl 5 "Perl6::..." Packages
* All of the github projects whose names start with "Perl6-"
* NQP
* Various internals (e.g. 6model)

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
