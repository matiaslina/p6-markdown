Example Usage
-------------

    use Text::Markdown;
    my $md = Text::Markdown.new($raw-md);
    say $md.render;

or

    use Text::Markdown;
    my $md = parse-markdown($raw-md);
    say $md.to_html;

## Who

Initial version by [Andrew Egeler](https://github.com/retupmoca), with
extensive additions by [JMERELO](https://github.com/JJ)
and [Altai-man](https://github.com/Altai-man)

