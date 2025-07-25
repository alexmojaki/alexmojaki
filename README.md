<p align="center">
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img src="https://github-readme-stats-six-nu-21.vercel.app/api?username=alexmojaki&show_icons=True&theme=tokyonight"
         alt="GitHub stats (refresh the page and it should load this time)"/>
  </a>
</p>

----

<img src="images/icons8-love-48.png" width="24" alt="love"/> <img src="images/icons8-python.svg" width="24" alt="python"/> I love Python, metaprogramming, and making programming easier.

My main project is [**futurecoder**](https://futurecoder.io/), a platform for self-learning Python for beginners. It depends on a lot of my other work on GitHub, most of which is mentioned below.

I'm an expert at extracting obscure but useful information from Python:

<details open>
<summary><b>🐛 Debuggers:</b></summary>
  
- [![1.7k stars](https://img.shields.io/github/stars/alexmojaki/birdseye?label=%E2%AD%90&style=plastic) `birdseye`](https://birdseye.readthedocs.io/en/latest/) is a unique and powerful debugger that lets you see the value of every individual expression:

  <img src="https://i.imgur.com/rtZEhHb.gif" height="96px" alt="birdseye demo 1"/>

  <img src="https://i.imgur.com/236Gj2E.gif" height="96px" alt="birdseye demo 2"/>

  <sub>*(Click thumbnails to expand them)*</sub>

- [![1.4k stars](https://img.shields.io/github/stars/alexmojaki/snoop?label=%E2%AD%90&style=plastic) `snoop`](https://github.com/alexmojaki/snoop) is a simple convenient debugger that logs everything a function is doing:

  <img src="https://i.imgur.com/Enu7k0h.png" width="96px" alt="snoop demo"/>

  It's based on [![16.5k stars](https://img.shields.io/github/stars/cool-RR/PySnooper?label=%E2%AD%90&style=plastic) `cool-RR/PySnooper`](https://github.com/cool-RR/PySnooper) for which [I made many major contributions](https://github.com/cool-RR/PySnooper/pulls?q=author%3Aalexmojaki+is%3Amerged) and am a collaborator.

- [![1.8k stars](https://img.shields.io/github/stars/alexmojaki/heartrate?label=%E2%AD%90&style=plastic) `heartrate`](https://github.com/alexmojaki/heartrate) visualises execution in real time:

  <img src="https://media.giphy.com/media/H7wUw65MLvHLoX4sMW/giphy.gif" width="96px" alt="heartrate demo"/>

  <img src="https://media.giphy.com/media/VIQqY8yyjYkhNfwF29/giphy.gif" width="96px" alt="heartrate stacktrace demo"/>

</details>

<details>
<summary><b>⚠️ Tracebacks:</b></summary>

- [`stack_data`](https://github.com/alexmojaki/stack_data) extracts data from stack frames and tracebacks, particularly to display more useful tracebacks than the default.
- I used `stack_data` to [overhaul tracebacks in **IPython**](https://github.com/ipython/ipython/pull/11886), adding several fixes and enhancements. In particular `stack_data` uses [`executing`](https://github.com/alexmojaki/executing) (see Magic section) to highlight the precise operation which failed:

  <img src="https://user-images.githubusercontent.com/3627481/75476425-3e6b9280-59a3-11ea-9b6c-b9e099475a45.png" width="96px" alt="ipython traceback with highlighted operation demo"/>

- `stack_data` is also used to show excellent beginner-friendly tracebacks in [futurecoder](https://futurecoder.io/):

  <img src="https://raw.githubusercontent.com/alexmojaki/futurecoder/master/images/traceback.png" width="96px" alt="futurecoder traceback"/>

- I added an [integration for the **Sentry** Python client](https://docs.sentry.io/platforms/python/configuration/integrations/pure_eval/) to provide more information in tracebacks in error reports. It uses my library [`pure_eval`](https://github.com/alexmojaki/pure_eval), which evaluates simple expressions such as attributes while guaranteeing that no potentially problematic code is executed. `pure_eval` is also used by `stack_data`.

</details>

<details>
<summary><b>✨ Magic:</b></summary>

- [![358 stars](https://img.shields.io/github/stars/alexmojaki/executing?label=%E2%AD%90&style=plastic) `executing`](https://github.com/alexmojaki/executing) can find the exact operation being executed by a frame. This is the only library that allows doing this reliably as it is a very hard problem. Many others have tried and failed.
- I used `executing` to overhaul [![9.8k stars](https://img.shields.io/github/stars/gruns/icecream?label=%E2%AD%90&style=plastic) `gruns/icecream`](https://github.com/gruns/icecream/pull/33) and [![336 stars](https://img.shields.io/github/stars/pwwang/python-varname?label=%E2%AD%90&style=plastic) `pwwang/python-varname`](https://github.com/pwwang/python-varname/issues/3#issuecomment-616206560), fixing several issues in the process. Both authors made me collaborators, and I've provided plenty of help since.
- [![417 stars](https://img.shields.io/github/stars/alexmojaki/sorcery?label=%E2%AD%90&style=plastic) `sorcery`](https://github.com/alexmojaki/sorcery) uses `executing` to provide several surprising magical functions.

</details>

<details>
<summary><b><img src="images/icons8-java-48.png" width="24" alt="java"/> <img src="images/icons8-amazon-web-services-50.png" width="24" alt="aws"/> <img src="images/Ruby_logo.svg" width="24" alt="ruby"/> <img src="images/icons8-kotlin-50.png" width="24" alt="kotlin"/> <img src="images/icons8-android-os-50.png" width="24" alt="android"/> Other: </b></summary>

- I use [![183 stars](https://img.shields.io/github/stars/gristlabs/asttokens?label=%E2%AD%90&style=plastic) `gristlabs/asttokens`](https://github.com/gristlabs/asttokens) in *all* the projects mentioned above! I've made [many significant contributions](https://github.com/gristlabs/asttokens/pulls?q=is%3Amerged+author%3Aalexmojaki) to it.
- [![132 stars](https://img.shields.io/github/stars/alexmojaki/instant_api?label=%E2%AD%90&style=plastic) `instant_api`](https://github.com/alexmojaki/instant_api) is more metaprogramming, but based on type hints. It lets you instantly create a Flask API with automatic type conversions, JSON RPC, and a Swagger UI. No other library makes this so convenient. Inspired by FastAPI.
- [![211 stars](https://img.shields.io/github/stars/alexmojaki/s3-stream-upload?label=%E2%AD%90&style=plastic) `s3-stream-upload`](https://github.com/alexmojaki/s3-stream-upload) lets you efficiently stream large amounts of data to AWS S3 in Java.
- [SunHours](http://sunhoursplugin.com/) is a SketchUp plugin written in Ruby used by architects around the world to analyse and visualise how much sunlight hits a surface. ([repo](https://github.com/alexmojaki/sunhours))
  
  <img src="https://sunhoursplugin.com/img/6.png" width="96px" alt="SunHours screenshot"/>

- [Quiggles](https://play.google.com/store/apps/details?id=com.alexmojaki.quiggles) is an Android app written in Kotlin that lets anyone draw beautiful animated patterns with ease. [<img src="images/icons8-play-button.svg" width="24" alt="play"/> Watch a quick demo (1:31)](https://www.youtube.com/embed/l4fGBsNi0IU?vq=hd1080). ([repo](https://github.com/alexmojaki/quiggles))

  <img src="images/quiggles/medium/s1%202021-03-03T18_06_57.gif?raw=true" width="96px" alt="Quiggles demo 1"/>
  <img src="images/quiggles/medium/hi%202021-03-03T18_05_00.gif?raw=true" width="96px" alt="Quiggles demo 2"/>
  <img src="images/quiggles/medium/s2%202021-03-03T18_07_45.gif?raw=true" width="96px" alt="Quiggles demo 3"/>

</details>

<sub>*(Click title text \[not icons\] to expand)*</sub>

----

<p align="center">
<a href="https://stackoverflow.com/users/2482744/alex-hall"><img src="https://stackoverflow.com/users/flair/2482744.png?theme=dark" width="208" height="58" alt="profile for Alex Hall at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for Alex Hall at Stack Overflow, Q&amp;A for professional and enthusiast programmers"></a>
</p>

<p align="center">
<a href="https://www.linkedin.com/in/alex-hall-8532079a/"><img src="images/icons8-linkedin-50.png" width="24" alt="linkedin"/></a> <a href="mailto:alex.mojaki@gmail.com"><img src="images/icons8-gmail-50.png" width="24" alt="email"/></a> <a href="https://opencollective.com/futurecoder"><img src="images/open-collective.svg" width="24" alt="opencollective"/></a>
</p>

<sub>*(Most logos from [icons8](https://icons8.com/), see full credits [here](https://github.com/alexmojaki/alexmojaki/tree/master/images))*</sub>
