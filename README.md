![parrots logo][parrots-logo-large]

 [Parrots]
===================


 Introduction
--------------

Simple web service that outputs what it has been given as input with a prefix added.

 Installation
--------------

1. Clone this repository
2. Run `composer install`
3. Configure a webserver to host the contents of the `web` directory under a domain root
4. Visit the domain in a browser
5. Fill out the input field and submit the form
6. Be amazed by the result

Usage
----------------

To change the colours or the prefix text, there are two options.

The easiest way is simply to edit the `default.json` file in the `config` directory.

A more advanced option is to add a new config file with a name that matches the
domain Parrots is run on. For exmple, if Parrots is hosted at `http://example.com`,
create the file `config/example.com.json`

    @TODO: Document all the config settings
    @TODO: Document GET params: http://jebentzelfeen.website/?subject=bar&prefix=foo&color=white&background-color=black

 Other info
----------------

To report bugs, feature requests or other issues, visit the [issues page]

### License

This project has been licensed under [GPL-3.0+ License][GPL-3.0+] (GNU General Public License v3.0 or higher).

### Origin

For a long time, the Dutch website http://jebentzelfeen.nl/ used to offer a
simple web service that would output what it has been given as input, with the
prefix "Je bent zelf een" added. This result could be used as a online retort
for many occasions.

When the service was no-longer available I started to miss it to a degree where
it seemed sensible to recreate the service myself.

I would like to thank the creators of the original concept, [Floor van Opijnen]
and [Mark Wittkampf], for the inspiration and that awesome original service.

### About the name

"Parrots" is the third-person singular simple present indicative form of the
verb "parrot". To quote fom a random dictionary:

>
> /ˈparət/
>
> ##Verb
>    **3rd person present**: *parrots*
>
>    Repeat mechanically.
>
> ##Synonyms
>
> repeat mindlessly, repeat, repeat mechanically, echo, say again
>
> ## Origin
> Early 16th century: probably from dialect French *perrot*, diminutive of the male given name Pierre.
>

### About the Logo

The logo uses the [Birds icon] designed by [Michela Tannoia] from [the Noun Project]
licensed under a [CC BY 3 License] (Creative Commons Attribution License).

[Michela Tannoia]: http://thenounproject.com/michela.tannoia/
[Floor van Opijnen]: https://www.facebook.com/floortjevanopijnen
[Mark Wittkampf]: https://twitter.com/wittkampf
[Birds icon]: http://thenounproject.com/term/birds/112329/
[the Noun Project]: http://www.thenounproject.com
[CC BY 3 License]: https://creativecommons.org/licenses/by/3.0/
[GPL-3.0+]: ./LICENSE
[issues page]: https://github.com/potherca/Parrots/issues
[parrots-logo-large]: ./parrots-logo-250.png
[Parrots]: https://github.com/potherca/Parrots/

