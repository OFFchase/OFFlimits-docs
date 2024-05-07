# Telegram results

## About

Use [OFFlimits telegram bot](https://t.me/OFFlimits_bot) to calculate your game results in just a few seconds.

<YandexAD blockId='R-A-8300744-3'></YandexAD>

## Example

<div style="display:flex;justify-content:center;margin-top:15px">
<video style="max-width:230px" controls autoplay loop>
  <source src="https://firebasestorage.googleapis.com/v0/b/offlimits-bot.appspot.com/o/dashboard%2Fvideos%2Ftelegram-results.mp4?alt=media" type="video/mp4">
  Your browser does not support the video tag.
</video>
</div>

## Usage

Lets say we have the results of 2 games for `Team One`.
**Input**

```txt:no-line-numbers
10th place                     1st place
Player A      3 kills          Player A      5 kills
Player B      1 kills          Player B      2 kills
Player C      0 kills          Player C      4 kills
Player D      1 kills          Player D      1 kills
```

::: tip
If the team name has numbers in it or the team name is a number, write it within `[ ]` brackets, Ex: `[Team 99]`
:::

- In our example case the name is Team One

Now we array points after name in the following order:

`Team Name [rank 1] [kills 1] [rank 2] [kills 2] and so on to infinity.`

::: warning
All teams should be in one message.
:::
