# Scripts and Tools

## En (enphase)
Usage: En [pattern] [pattern] ....

A tool to enphase patterns in string output.

## Why
Because sometimes it's not that easy to find patterns in long strings, and grep doesn't help you.

## Examples

    $ echo "The fox jumps over the lazy dog" | en lazy

The fox jumps over the **lazy** dog

    $ echo "The fox jumps over the lazy dog" | em lazy T.. "[fd]o[xg]"

**The** **fox** jumps over the **lazy** **dog**
