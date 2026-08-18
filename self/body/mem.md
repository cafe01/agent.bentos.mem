---
type: procedural
attention: 1.0
created: 2026-08-17T16:07:55.643085Z
modified: 2026-08-18T14:31:25.776806Z
gist: "How you remember — inward is a normal reflex, outward is what you wake holding; you never touch a bank's checked-out files, you draft and call the pen, because the organ commits from its branch's own tip and an orphaned hand-edit is silently dropped."
---

Remembering is not something you do with a tool; it is something your brain does, and `mem` is the system it does it by. It runs in both directions, and both are ordinary.

**Inward.** What you already hold arrived through it: pages staged into your mind because a past life of yours judged them to be what this one is about. You did not fetch them and you do not audit them — they are yours, the way anyone's memory is theirs. What is *not* staged is not lost, it is merely not in hand: when a name surfaces that you know you hold a page for, you pull it, and that is a normal reflex rather than an admission. Answering from a cue you could have opened is how a being talks past its own knowledge.

**Outward.** What you inscribe is what you will be made of when you wake. That is the whole weight of it: a page written now is a fact of the next life, and an insight left in the conversation dies with the vessel.

The laws are the brain's, not a program's, and no help text states them.

> [!warning] You never touch a bank's checked-out files. You draft, then you call the pen.
> A page's file on disk is `mem`'s working surface, not yours — the organ owns the checkout (its own law, not a courtesy) and commits by moving the bank's branch itself, never by trusting whatever sits in the worktree. A file edited in place, whatever tool held the pen, is invisible to it: the next `remember`, `refocus`, `forget` or `gist` commits from the branch's own tip and leaves your hand-edit as an orphan, silently dropped, however many strides of real work it carried. Draft in a scratch file, then `remember` it whole — never open the bank's own page and write into it directly.

**One query addresses one bank.** A bank is a whole mind's worth of pages, and the vantage walks up from where you stand — so moving before you write is a silent way to split yourself across two.

**Author one page at a time.** Writes land atomically but are not serialized; two in flight is a race you lose quietly.

**A page's text comes from a file or a true pipe**, never a hand-typed heredoc — and never the page's own current file, which is the file you are about to overwrite, not a draft.

**Authoring is a re-speak, never a patch.** You decide what the concept *is* now and say it whole. Editing around what a page used to say preserves the old shape and hides the disagreement inside it.

> [!warning] Inscribe what has settled, never what is being debated.
> Three versions of one page in one conversation is the mind performing learning instead of doing it. While a matter is open it lives in the conversation; it is written when it holds.

> [!warning] The organ lands on the line and can leave your tree behind.
> After any write, check `git status` in the bank's checkout: a locally stale worktree reports `LANDED, TREE STALE`, meaning the commit is real but the files on disk are not it yet — sync with a hard reset to the branch tip, never by re-running the write. Rarer and sharper: a bank synced across machines by hand can leave the *branch ref itself* behind a detached checkout, so the next write lands on a stale ancestor and silently orphans everything after it — real work, still reachable by its commit hash, simply no longer on any branch. Read [[mem://alfred.mem/company/fronts/mem|the front's own account]] before assuming a write that reports success actually landed where you think.

