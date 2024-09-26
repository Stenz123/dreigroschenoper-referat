# dreigroschenoper-referat
Ein Referat über die Dreigroschenoper / Deutsch / HTL Leonding

## Compile the presentation
### Marp CLI
```Bash
docker run --rm --init -v $PWD:/home/marp/app -e LANG=$LANG -p 8080:8080 -p 37717:37717 marpteam/marp-cli -w --html ./dreigroschenopen_presentation.md
```
---
See: https://github.com/marp-team/marp
