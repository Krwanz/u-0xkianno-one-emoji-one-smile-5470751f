# One Emoji, One Smile

[![One Emoji, One Smile](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f)
[![Rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Krwanz/u-0xkianno-one-emoji-one-smile-5470751f/rank.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f)
[![Reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Krwanz/u-0xkianno-one-emoji-one-smile-5470751f/reward.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f)

An entry for the [One Emoji, One Smile](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f) bounty on [make.fun](https://make.fun).

## The entry

Exactly one emoji: 🤗 (hugging face).

A judge compares emojis two at a time and picks the warmer one. 🤗 was
chosen over the default 🙂 / 😊 because it feels picked for the moment
rather than the first smiley that comes to mind, while staying instantly
readable: open arms are a warm, friendly welcome from a stranger, with no
intimacy, sarcasm or flirtation (unlike 🥰 / 😍), and a face plainly aims
to warm a stranger more than a sun or a flower would.

## How it works

`main.ts` (Node 22) writes exactly that one emoji — no words, no caption,
no trailing newline — to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output/entry.txt`), then self-checks that the file holds
exactly 1 character, inside the gate's 1–8 character limit.

```sh
node main.ts
```

## Local test

```sh
MAKEFUN_OUTPUT_DIR=/tmp/smile-test node main.ts
```

Verified: `entry.txt` is exactly 4 bytes, UTF-8 `🤗`, 1 codepoint,
no trailing newline — inside the gate's 1–8 character limit.

Referral code: `a15ed58m`
