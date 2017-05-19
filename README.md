# midbot-wikipedia

A Hubot script for interacting with [Wikipedia's API](https://en.wikipedia.org/w/api.php) (searching for articles and returning extracts).

See [`src/wikipedia.coffee`](src/wikipedia.coffee) for full documentation.

Forked and edited with Mid's personality for [MidBot][midbot].

[midbot]: https://github.com/ProbablyAimee/MidBot

## Commands

Command | Listener ID | Description
--- | --- | ---
hubot wiki `query` | `wikipedia.search` | Returns the first 5 Wikipedia articles matching the search `query`
hubot tell me about `article` | `wikipedia.summary` | Returns a one-line description about `article`


## Sample Interaction

```
user1>> hubot tell me about clean room design
hubot>> Clean room design: Clean room design (also known as the Chinese wall technique) is the method of copying a design by reverse engineering and then recreating it without infringing any of the copyrights and trade secrets associated with the original design. Clean room design is useful as a defense against copyright and trade secret infringement because it relies on independent invention.
hubot>> Original article: https://en.wikipedia.org/wiki/Clean%20room%20design
```
