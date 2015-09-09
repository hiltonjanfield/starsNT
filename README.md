# StarsNT

This repository is a placeholder. Although the project is in (slow) active development, there are no plans to upload it until a stable, usable point has been reached, OR there is significant interest from other developers in contributing.

This decision has been made primarily due tothe numerous Stars! clone projects that have failed, stalled, or been abandoned over the last 20 years. I do not want to publicly announce or promote the project until a *minimally-playable version* is online, akin to an alpha or early beta release. Those who want to see the current progress can do so at the [StarsNT Demo](http://www.janfield.ca/starsnt/).

## About StarsNT

StarsNT is a re-imagining or reboot of the classic 4X strategy game [Stars! 2](http://en.wikipedia.org/wiki/Stars!) (also referred to as "Classic Stars"). The goal is not to clone the game - instead, the goal is to build a game engine that is capable of reproducing the original game as well as being extended and providing game play for games with all sorts of different rules, extended graphics, and more, to cater to all the ideas what major Stars! players have had over the years.

StarsNT is centred around rulesets. Rather than being hard coded, customizble rulesets define everything in the game.

StarsNT is written using PHP 5.5 and Yii 2.0, and makes extensive use of the technologies behind HTML 5, CSS 3, and JavaScript.

Those wishing to learn more or contribute can contact me directly at hilton@janfield.ca.

## Status

Current development status:
- Basic site in operation (see [StarsNT Demo](http://www.janfield.ca/starsnt).
- Ruleset editing and management systems ~60% complete.
- Classic style map builder complete, generates maps that look very close to the original game in both standard and clumping mode (see [StarsNT Map Builder Devtoy](http://www.janfield.ca/starsnt/dev/startmaptest)).
- Classic Stars ruleset 95% built, including all technologies and components (see [Classic Stars Ruleset](http://janfield.ca/starsnt/ruleset/1); register/login and select "Copy to Personal Library" to be able to play around with the editor).
- Debugging user-scriptable functions for the ruleset, using a PHP-based JavaScript engine (see [hiltonjanfield/js4php5](https://github.com/hiltonjanfield/js4php5)). Functionally complete to the level required, but is also easily broken.
- UI design testing in progress (see [UI test](http://www.janfield.ca/starsnt/dev/uitest)).
- DOM-based map display at basic functional level (see [UI test](http://www.janfield.ca/starsnt/dev/uitest)). Most browsers seem to have no trouble displaying the required 3,000 elements, even on mobile.
- Canvas-based map display in testing. So far, testing finds that browsers have difficulty with a large size 2000x2000 pixel multi-layer map...that, or I'm doing something really wrong. Canvas pros, email me!
- Modification and improvement of components to be used in the UI also in progress (see [jquery.enhsplitter](https://github.com/hiltonjanfield/jquery.enhsplitter), [yii2-jquery.enhsplitter](https://github.com/hiltonjanfield/yii2-jquery.enhsplitter), and more to come).
- Design considerations on how to implement customizable graphics in progress.

## What's the "NT"?

Take your pick.

- New Technology
- New Tomorrow
- No Time
- No Tomorrow
- Not Tested
- Nikki Tyler
- *[insert witty expanded acronym of your choosing here]*
