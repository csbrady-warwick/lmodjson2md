# lmodjson2md
Convert output of spider -o jsonSoftwarePage $MODULEPATH to simple markdown

To run, use as spider -o jsonSoftwarePage $MODULEPATH | lmodjson2md > page.md

The resulting markdown is Github flavoured markdown and can be rendered natively on Github or converted to HTML through tools such as Pandoc that support github flavoured markdown. This is still very, very primitive so don't rely in it too much!
