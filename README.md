#Installation#

    cp editor_plugin.py ~/.config/terminator/plugins/

#Configuration#

file: ~/.config/terminator/config

    ... 
    [plugins]
        ...
        [[EditorPlugin]]
            command = {filepath}
            editor = kate
            match = [^ \t\n\r\f\v:]+?\.(ini|conf|me|txt|xml|json)[ \n:]([0-9]+)* 
