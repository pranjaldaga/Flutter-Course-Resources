PROBLEM: https://cisco.udemy.com/course/flutter-bootcamp-with-dart/learn/lecture/17119664#overview
Followed all steps and still echo $SHELL gives /bin/bash

SOLUTION: Probably. $SHELL is the path to your default shell, so it seems like your default shell didn't get changed to zsh. If this is the case, you can fix it yourself with chsh -s /bin/zsh.
SOURCE: https://github.com/ohmyzsh/ohmyzsh/issues/4596
