I enjoy metaprogramming and making programming easier.

My main project is [futurecoder](https://futurecoder.io/), a platform for self-learning Python for beginners. It depends on a lot of my other work on GitHub, most of which is mentioned below. I'm looking for contributors, partnerships, [funding](https://opencollective.com/futurecoder), and work in a similar space.

I'm an expert at extracting obscure but useful information from Python:

**Debuggers**

- [`birdseye`](https://birdseye.readthedocs.io/en/latest/) (![1.4k stars](https://img.shields.io/github/stars/alexmojaki/birdseye?label=%E2%AD%90&style=plastic)) is a unique and powerful debugger that lets you see the value of every individual expression:

  ![birdseye demo](https://i.imgur.com/rtZEhHb.gif)

- [`snoop`](https://github.com/alexmojaki/snoop) (![462 stars](https://img.shields.io/github/stars/alexmojaki/snoop?label=%E2%AD%90&style=plastic)) is a simple convenient debugger that logs everything a function is doing:

  ![snoop demo](https://i.imgur.com/aBVXFSQ.png)

  It's based on [cool-RR/PySnooper](https://github.com/cool-RR/PySnooper) (![14.2k stars](https://img.shields.io/github/stars/cool-RR/PySnooper?label=%E2%AD%90&style=plastic)) for which [I made many major contributions](https://github.com/cool-RR/PySnooper/pulls?q=author%3Aalexmojaki+is%3Amerged) and am a collaborator.

- [`heartrate`](https://github.com/alexmojaki/heartrate) (![1.1k stars](https://img.shields.io/github/stars/alexmojaki/heartrate?label=%E2%AD%90&style=plastic)) visualises execution in real time:

  ![heartrate demo](https://media.giphy.com/media/H7wUw65MLvHLoX4sMW/giphy.gif)

  ![heartrate stacktrace demo](https://media.giphy.com/media/VIQqY8yyjYkhNfwF29/giphy.gif)

**Tracebacks**

- [`stack_data`](https://github.com/alexmojaki/stack_data) extracts data from stack frames and tracebacks, particularly to display more useful tracebacks than the default.
- I used `stack_data` to [overhaul tracebacks in **IPython**](https://github.com/ipython/ipython/pull/11886), adding several fixes and enhancements. In particular `stack_data` uses [`executing`](https://github.com/alexmojaki/executing) (discussed below) to highlight the precise operation which failed:

  ![ipython traceback with highlighted operation demo](https://user-images.githubusercontent.com/3627481/75476425-3e6b9280-59a3-11ea-9b6c-b9e099475a45.png)

- `stack_data` is also used to show excellent beginner-friendly tracebacks in [futurecoder](https://futurecoder.io/):

  ![futurecoder traceback](https://raw.githubusercontent.com/alexmojaki/futurecoder/master/images/traceback.png)

- I added an [integration for the **Sentry** Python client](https://docs.sentry.io/platforms/python/configuration/integrations/pure_eval/) to provide more information in tracebacks in error reports. It uses my library [`pure_eval`](https://github.com/alexmojaki/pure_eval), which evaluates simple expressions such as attributes while guaranteeing that no potentially problematic code is executed. `pure_eval` is also used by `stack_data`.

**Magic**

- [`executing`](https://github.com/alexmojaki/executing) (![68 stars](https://img.shields.io/github/stars/alexmojaki/executing?label=%E2%AD%90&style=plastic)) can find the exact operation being executed by a frame. This is the only library that allows doing this reliably as it is a very hard problem. Many others have tried and failed.
- I used `executing` to overhaul [gruns/icecream](https://github.com/gruns/icecream/pull/33) (![2.3k stars](https://img.shields.io/github/stars/gruns/icecream?label=%E2%AD%90&style=plastic)) and [pwwang/python-varname](https://github.com/pwwang/python-varname/issues/3#issuecomment-616206560) (![81 stars](https://img.shields.io/github/stars/pwwang/python-varname?label=%E2%AD%90&style=plastic)), fixing several issues in the process. Both authors made me collaborators, and I've provided plenty of help since.
- [`sorcery`](https://github.com/alexmojaki/sorcery) (![285 stars](https://img.shields.io/github/stars/alexmojaki/sorcery?label=%E2%AD%90&style=plastic)) uses `executing` to provide several surprising magical functions.

**Other notable work**

- I use [`gristlabs/asttokens`](https://github.com/gristlabs/asttokens) (![86 stars](https://img.shields.io/github/stars/gristlabs/asttokens?label=%E2%AD%90&style=plastic)) in *all* the projects mentioned above! I've made [many significant contributions](https://github.com/gristlabs/asttokens/pulls?q=is%3Amerged+author%3Aalexmojaki) to it.
- [`instant_api`](https://github.com/alexmojaki/instant_api) (![103 stars](https://img.shields.io/github/stars/alexmojaki/instant_api?label=%E2%AD%90&style=plastic)) is more metaprogramming, but based on type hints. It lets you instantly create an HTTP API with automatic type conversions, JSON RPC, and a Swagger UI. No other library makes this so easy.
- [`s3-stream-upload`](https://github.com/alexmojaki/s3-stream-upload) (![149 stars](https://img.shields.io/github/stars/alexmojaki/s3-stream-upload?label=%E2%AD%90&style=plastic)) lets you efficiently stream large amounts of data to AWS S3 in Java.
- [SunHours](http://sunhoursplugin.com/) is a SketchUp plugin written in Ruby used by architects around the world to analyse and visualise how much sunlight hits a surface.
- [Quiggles](https://play.google.com/store/apps/details?id=com.alexmojaki.quiggles) is an Android app written in Kotlin that lets anyone draw beautiful animated patterns with ease.
