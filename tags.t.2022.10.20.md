---
id: 0mkkm4y3za52ju70vypo9me
title: 2022.10.20
desc: the day I figured out how to do time in Dendron
updated: 1703094885142
created: 1666330812115
---

## Thoughts

- t.2023.12.20.09 ^6rpm36f0v9cq
  - keep backlinks semantically useful. You can always use search to find everything you did on a certain time hierarchy
  - so... probably no reason not to use un-namespaced ISO-ish? e.g. 2023-12-20T09
    - well, the obvious reason is so you don't accidentally include things like urls or identifiers that match yyyy or yyyy-mm


## Archive

- a collection of empty notes (although adding content couldn't hurt... what would it be? Thoughts about that time? )
- public vs. private
  - since there's not much content, public should be fine
  - but it does leak "something refers to this date", i.e., if your supposed to be on vacation, or how much work you do
- utility is mostly for backlinks... "all the stuff I did on day x", but unfortunately backlinks panel is hierarchy friendly
  - [[pi.dendron.backlinks-from-sub-hierarchy]] ideally you'd want to see all backlinks to all sub-notes somehow

the title should probably use dots too, to be consistent, but hopefully could be left up to user preference? yikes. Well, "filesystem-first" is a holy principle, and the congruency between hierarchy and temporal divisions is sweet. Periods it is. So, unconventionally(and likely rarely), we introduce a new syntax... Should it be YYYY.MM.DD.hh.ss.s* with no option for am/pm? Ugly, but hopefully we can get used to it. Call it [[pi.dendron-compatible-date-format]].
- since dash is used for word spacing, it's really gotta be periods. I'll change the journal schema.
- only top result is [YYYY.MM.DD.HH.SS.DocumentName I what each, and every, document to have this format via AI - Google Account Community](https://support.google.com/accounts/thread/31439065/yyyy-mm-dd-hh-ss-documentname-i-what-each-and-every-document-to-have-this-format-via-ai?hl=en)
- certainly not in https://learn.microsoft.com/en-us/dotnet/standard/base-types/standard-date-and-time-format-strings
- https://wiki.dendron.so/notes/k5s3fpricnca8vk5zhvgsf6/

## daily journal template

description blank
first line: ## [[YYYY.MM.DD.HH]] 
  - minutes is to narrow, should only be when you really need temporal precision

[Journal Note](https://wiki.dendron.so/notes/uz13dadm4umn3882awr1087/)