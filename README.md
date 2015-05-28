Example Usage
-------------

    use Text::Markdown;
    my $md = Text::Markdown.new($raw-md);
    say $md.render;

or

    use Text::Markdown;
    my $md = parse-markdown($raw-md);
    say $md.to_html;
