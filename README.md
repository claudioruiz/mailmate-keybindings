# MailMate KeyBindings

My personal MailMate keybindings file

## Focus

This keybindings file is focused on keyboard email handling so it has some easy keystrokes for moving between messages in a single mailbox and also moving between mailboxes.  It has a mix of typical vi keybindings (j/k for message navigation) and some other command line tools mixed in, like you can do `g` or `G` to go to the top or bottom of a mailspool like in less.

## Key Layout

* Navigation within a mail spool
  * **j** Move to the next row
  * **k** Move to the previous row
  * **l** Expand a thread and move to the next unread message (if you open a thread without unread messages, this jumps to next unread mailspool message but not necessarily in the thread)
  * **h** Collapse a thread
  * **g** Jump to the first message
  * **G** Jump to the last message
* Navigation between folders
  * **J** Next folder
  * **K** Previous folder
  * **option-J** Next folder with unread messages
  * **option-K** Previous folder with unread messages
* Messages Actions
  * **space** Scroll a page down in the currently displayed message
  * **shift-space** Scroll a page up in the currently displayed message
  * **u** Toggle the read state
  * **a** Archive
  * **s** Toggle flag (star)
  * **r** Reply
  * **a** Reply-all
  * **f** Forward
  * **#** Delete
  * **!** Move to junk
* General
  * **/** Search
  * **z** Undo
  * **Z** Redo

## Installation

Copy the `claudio.plist` file into `~/Library/Application Support/MailMate/Resources/KeyBindings` then type "claudio" into the "Custom Key Bindings" field in the General section of settings.

## What is MailMate?

It's a great IMAP mail client for Mac OS X.  Look here: https://freron.com

It solved my eternal search for a great, customizable and lightweight email app in OSX.

If you buy it, you should consider becoming a patron: https://sites.fastspring.com/freron/product/mailmatepatron?referrer=5954
