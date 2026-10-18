# vestigecounty/tap

Homebrew formulae for [ThinkBoard](https://vestigecounty.github.io/thinkboard/) — your Obsidian canvas, over everything.

```sh
brew install vestigecounty/tap/thinkboard
brew services start thinkboard   # now, and at every login
```

Or open it once, as an app: `open $(brew --prefix)/opt/thinkboard/ThinkBoard.app`.

`Formula/thinkboard.rb` is written by ThinkBoard's release workflow on every release, from
[`packaging/homebrew/thinkboard.rb`](https://github.com/vestigecounty/thinkboard/blob/main/packaging/homebrew/thinkboard.rb)
— change it there, not here.
