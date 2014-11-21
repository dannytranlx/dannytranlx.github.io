---
layout: posts
title:  "Setting up my new laptop"
date:   2014-11-20 21:21:06
background: posts/macbookpro.jpg
---

Every developer have their own work environment, a well-crafted set of keyboard shortcuts and an oiled workflow with a specific tool belt. Getting a new laptop or workstation is always a start over to set everything as it used to be to get back into the code as fast as possible. I am writing it to share what are the tools I am using, but also to make a reference to myself.

So I just started working at [Radialpoint](http://radialpoint.com) and they got me a new MacBook Pro 13” with Retina display (great upgrade from my old MacBook Pro 13” with no Retina display). I’m a sucker for details and sharpness and this laptop’s screen gives me both, it’s so awesome.

## Update OS X

First thing first, upon the unwrapping, it was still on 10.9 Mavericks so I bumped it up to the newly released 10.10 Yosemite (my calculus mind still can’t wrap around how 10.10 can be a “number” :unamused:).

## Web browsers & emails

Right after I booted on, I went on Safari and grabbed Chrome. I love Safari for how optimized it is on OS X, but doing web development, Chrome’s Developer Tools kills it! Signed on my Google Account and I started to see all my Extensions and Bookmarks come in. Great, I already feel at home. (Also threw Firefox in there for cross-browsing tests)

To set up Calendar, Mail, Contacts, Messages and Notes, I went on `Internet Accounts` in the `System Preferences` to add my Google account. Events, contacts, emails are also syncing in.

## Development tools

The main tool for a web developer now a days is his text editor. My main editor is still jumping between [Vim](http://en.wikipedia.org/wiki/Vim_(text_editor)) and [Sublime Text](www.sublimetext.com). I installed them both. I really need to get my Vim on point, but I still feel a little unproductive. _I promise I will get at it by 2015_. I don’t wanna be too unproductive to my new teammates right now!

The other tool right next to the text editor is obviously the Terminal. I use [iTerm2](http://iterm2.com/), but I forgot what are really the avantages over the regular Terminal. However, I mapped `^t` to show and hide my terminal on demand. It’s kind of useful to pop on Terminal without going through several `Cmd+Tab` or left/right swipes.

Along with my terminal, I have [Oh-My-Zsh](http://ohmyz.sh/) to add completions or some lulz (lolbash and telnet’ing to a Nyan Cat). With [Homebrew](http://brew.sh), I installed tmux and several packages I needed to work it (nodejs for exemple). Since @laurentdang hooked me on Vim, he also got me on tmux. [tmux](http://tmux.sourceforge.net/) is a terminal multiplexer which means it lets split your terminal into several views and screens all handle inside your terminal with multiple commands and keystrokes. I symlinked back my [dotfiles](https://github.com/dannytranlx/dotfiles) to everything was back in order for zsh, vim, tmux and git configs.

## Daily useful apps

Great, most of the work is done, I could start to work but I have a few more apps to install. Instead of Spotlight, I use [Alfred 2](http://www.alfredapp.com/). I find it more seamline than Spotlight, especially since Yosemite, Apple added tons of stuff to Spotlight, it’s almost useless. I launch Alfred with `Cmd+Space` to open apps or make quick calculations with the integrated calculator. I didn’t dig deep enough on all Alfred’s features, but it’s promising (it can helps with workflow and open GitHub and stuff).

Talking about GitHub, we are working with pull requests and the best way to work with pull requests is to add images or gifs. To handle my screenshot madness, I use [CloudApp](https://www.getcloudapp.com/). CloudApp can grab my images, screenshots or screencaptures, throw them on its servers and copy the link to my clipboard ready to paste to a chat room or on a pull request. I use CloudApp daily and find it highly effective in my daily screenshot sending.

Other than that I got [Fantastical](https://flexibits.com/FANTASTICAL) to quickly manage my calendar events, TweetDeck for tweets, Spotify for music and Skype for IM (along with Facebook Chat, Google Hangout set up in Messages).

For the curious, I write a lot in french so I mapped a quick language change on `Ctrl+Space`. Fantastical is on `Ctrl+Alt+Space` and the most important is `Ctrl+Cmd+Space` for emoji madness :shit: :grin: :rocket: :zap:

I could say that the setup is done, but like a development, it’s going to keep evolving to answer to my requirements to be as productive as possible.

What are you using on your workstation? Share with me on Twitter @dannytranlx.
