# unproof

Script to unscramble proofpoint's urldefense URLs. Does not follow the link (and therefore does not tell proofpoint when you are reading your mail).

# Use with mutt

The following two settings ensure that URLs are shown unscrambled in mutt's pager and that URLs are unscrambled before editing a mail for replying:
```
set display_filter='/path/to/unproofpoint'                                                                                                                                                                
set editor='/path/to/unproofpoint %s; vim %s'
```
