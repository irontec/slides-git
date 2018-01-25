### logs
* Una vez creados varios commits, o tras clonar un repositorio, nos puede interesar ver el histórico

```shell
$ git log
commit 5be1f00a9a701532232f57958efab4be8c959a29 (HEAD -> master, origin/master, origin/HEAD)
Author: Junio C Hamano <gitster@pobox.com>
Date:   Tue Jan 23 13:21:10 2018 -0800

    First batch after 2.16

    Signed-off-by: Junio C Hamano <gitster@pobox.com>

commit e7e80778e705ea3f9332c634781d6d0f8c6eab64 (grafted)
Author: Junio C Hamano <gitster@pobox.com>
Date:   Tue Jan 23 13:16:41 2018 -0800

    Merge branch 'nd/add-i-ignore-submodules'

    "git add -p" was taught to ignore local changes to submodules as
    they do not interfere with the partial addition of regular changes
    anyway.

    * nd/add-i-ignore-submodules:
      add--interactive: ignore submodule changes except HEAD

```
