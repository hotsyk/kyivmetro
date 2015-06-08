Inspired by https://github.com/vbarbaresi/MetroGit

This Git repository contains the all metro stations from 3 Kyiv's lines.

You can visualize the result in many ways, for example:
- GitHub network view: https://github.com/hotsyk/kyivmetro/network
![GitHub network view](http://img.hotsyk.com/Network_Graph__hotsykkyivmetro__GitHub_2015-06-08_23-47-05.jpg)

- `git log --all --graph` (+ your favorite **decorate** options)

Each metro line is represented by a **branch**.

A **commit** corresponds to a station. All commits are empty (with `--allow-empty` option), there is only metadata in this repository (and this `README` file)

A **merge** is a connection between one or more lines.

