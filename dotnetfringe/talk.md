Code reuse, in the general case, is a myth. 

Functional languages are about taking the internals of a thing and dispatch and manipulate based on those in a way that is understandable

In a way that can be used and exposed

If something changes we've got enough structures in the language to realize that that we'll just go change what needs to be changed. @ericbmerritt @elixirfountain

Scratch
-------

Editors used, tools used, help found, documentation, guidance, references, deploying, testing, troubleshooting issues.

What is encourage in each. (no testing). Seed projects? 

[Presentation description goes here. Try to keep it under say, 500 words, but more than 140 characters]


App screenshot generator: https://developer.android.com/distribute/tools/promote/device-art.html

Use a different background color on first slide when beginning a new topic.


Talk
====

https://github.com/dotnetfringe/
http://seattlecc.azurewebsites.net/Account/Register
http://elixirconf.com/

Got to get people quickly or they'll still where they are comfortable or move to the next thing.
Clojure has ClojureScript, Elixir has Elm, Asp.net core has ?
Be positive!!!!
Include lots of tweets from the community to spin the story

Elixir
------

- So easy people are recreating their past environment in Elixir.
    - People come because the barrier looks really low, familiar with what you're already doing and sell it to your company. But then you hit the intermediate gap and its fundamentally not new.
- Separation between Elixir and Erlang communities
- OTP
- The repl
- Is it bad that Phoenix does everything. Is that like using asp.net mvc and hinders oss. As a beginner it is extremely helpful though
- Requests are often specified as tuples, like this, in order to provide more than one “argument” in that first argument slot http://elixir-lang.org/getting-started/mix-otp/genserver.html

- Mix
    - mix compile
    - umbrella projects
    - adds a .gitignore for you

https://www.youtube.com/watch?v=a-off4Vznjs&feature=youtu.be
- Pattern matching (removes the need for conditional statements)
    - tries to make the lhs side same as the rhs
    - destructoring
    - a = [1,2,3]
    - [b,c,d] = a
    - [b,c,3] = a
    - [b,c,4] = a
- Pipe operator (like threading operator in Clojure) 19:30

Clojure
-------

- Terrible errors
    - have to cataglog the errors https://github.com/yogthos/clojure-error-message-catalog/blob/master/clj/class-not-found-exception.md
- Terse (hard to read)
    - http://stackoverflow.com/questions/1894209/how-to-read-mentally-lisp-clojure-code
- Has ClojureScript
- Ring - no sockets, really? Okay I guess I can switch everything over to http-kit
- Emacs, although there are others (watching a screencast, started with atom, had to shift to emacs)
- The repl
- Code is data, data is code
- Academic, terse
- start up time (time lein repl)

    - Video
        - Hosted, many implementations
        - Good interop, trival to use Java code (opens a huge library)
        - list don't eval to themselves. First thing is an opeartion, the rest are arguments.
            - + is a symbol which evaluates to a function, hence why it can be in the operator position
        - recursive nature of evaluation, works from inner to the outer, eval as it goes
        - persistent data structures? Seems to complex to show
            - new values reuse the old values, structure is shared
        - ISeq interface. again probably too much
            - Clojure uses the ISeq interface to allow many data structures to provide access to their elements as sequences. The seq function yields an implementation of ISeq appropriate to the collection. http://clojure.org/reference/sequences



asp.net core
------------

- Editor: vscode really taking off, especially in the angular community
