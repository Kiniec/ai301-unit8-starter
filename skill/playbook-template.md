# Playbook: Mar Kiniec Carlisle

## Response rules

- Answer the reviewer's point in the first sentence, then say which file I changed.
- Paste results of any check I re-ran, and never write "all pass".
- For a bot review, I check each point against the source, fix the ones that hold
  up, and say which I skipped and why.

## Staleness thresholds

Seven quiet days, for a first review or a stalled one. Outside contributors' PRs
here usually merge in about 3 days, and the slowest recent one took 5. The monitor
counts bot comments as activity, so I check for the last human reply before I
nudge.

## Nudge etiquette

One nudge, after seven quiet days. It says in one sentence what the PR does,
asks one thing (whether it needs a change before review), and tags only
@DawoudIO, the maintainer who moved the issue. It never says "any update?". I
send a second nudge only if a maintainer replies and then goes quiet again.

## Walk-away criteria

I close the PR if a maintainer says the docs belong elsewhere or the pattern is
documented another way, if issue #202 is closed by someone else's PR, or if 21
days pass with no reply after my nudge (two older PRs here waited that long).
The close note says what the PR did, why I am closing it, and that the branch is
available if someone wants to reuse it.