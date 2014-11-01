Notmuch mail
============

[Notmuch](http://notmuchmail.org/) stands for _tags_ and _fast search_.

 * written in C (uses [Xapian](http://xapian.org/) as search backend)
 * super fast searching
 * enables you tag your mails
 * it _does_ not
  * downloads your mail from internet
  * provide user interface (sort of)
  * send your mails
  * tag your mail using sophisticated rules (but [afew](https://github.com/teythoon/afew) does)

## Receiving e-mails

* isync
* offlineimap

## Tagging e-mails

* afew

 * install it

  * `git clone https://github.com/teythoon/afew.git`
  * be sure to have gcc, python devel and dbacl
  * `./setup.py install --user`

 * check out default configuration (and put it to `.config/afew/config`)

 * tag your mails using `~/.local/bin/afew --tag --new`

## Browsing your mailbox

* [Emacs](http://notmuchmail.org/emacstips/)
* [vim](http://git.notmuchmail.org/git/notmuch/blob/HEAD:/vim/README)
* [mutt](http://notmuchmail.org/notmuch-mutt/)
* [mutt-kz](https://github.com/karelzak/mutt-kz)
* [alot](https://github.com/pazz/alot)
* [bower](https://github.com/wangp/bower)

## Misc

* sending emails
* address book

