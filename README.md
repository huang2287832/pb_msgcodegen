pb_msgcodegen
=====

A rebar plugin

Build
-----

    $ rebar3 compile

Use
---

Add the plugin to your rebar config:

    {plugins, [
        { pb_msgcodegen, ".*", {git, "git@host:user/pb_msgcodegen.git", {tag, "0.1.0"}}}
    ]}.

Then just call your plugin directly in an existing application:


    $ rebar3 pb_msgcodegen
    ===> Fetching pb_msgcodegen
    ===> Compiling pb_msgcodegen
    <Plugin Output>
