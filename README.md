# medium-editor-embed-button
You can embed any oEmbed supported media to your document by just

* paste url
* highlight it
* click **E** button, that's it!

## how to use
Reference script and styleshhet to page

    <link rel="stylesheet" href="/path/to/medium-editor-embed-button.min.css" type="text/css" media="screen" charset="utf-8">
    <script type="text/javascript" src="/path/to/medium-editor-embed-button.min.js"></script>

and create an MediumEditor instance with extension config.

        var editor = new MediumEditor('.editable', {
            buttonLabels: 'fontawesome',
            extensions: {
                embedButton: new EmbedButtonExtension()
            },
            toolbar: {
                buttons: [
                    'h2',
                    'bold',
                    'italic',
                    'unorderedlist',
                    'orderedlist',
                    'embedButton'
                ]
            }
    });

and try it :)

Don't hesitate to contribute.

cheers!