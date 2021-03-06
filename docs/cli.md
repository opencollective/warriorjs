---
id: cli
title: CLI
---

There are various options you can pass to the `warriorjs` command to customize
the game. You can run `warriorjs --help` to see all the available options.

Here is a detailed list:

## `--directory <path>`

Path to a directory under which to run the game. By default, the current working
directory is used.

> Running `warriorjs` while you are in your profile's directory will auto-select
> that profile so you don't have to each time.

## `--level <number>` (Epic Mode only)

Practice a level. Use this option on levels you are having difficulty or want to
fine-tune the scoring.

## `--skip`

Skip confirmation dialogs, choosing the default answer for each question (always
the most conservative).

## `--time <seconds>`

Delay each turn by seconds. By default, each step of each turn is delayed by 0.6
seconds.
