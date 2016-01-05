`bower install quartertobowertest-dep` puts `quartertobowertest` at `bower_components/quartertobowertest-b`

`bower install quartertobowertest-b` and `bower install quartertobowertest-a` put it at `bower_components/quartertobowertest-a`

`bower install --save quartertobowertest-b` puts it in `bower.json` as an alias: `"quartertobowertest-a": "quartertobowertest-b#*"`