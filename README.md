# Go-bh3-VisualNovel
Daemon server with HTTP interface designed to detect and achieve collections of Honkai3 visual novel.

## Requirements
- Golang SDK 1.11.4

## It CAN
- Get task with auth param from HTTP interface
- Check the credential provided (Sync)
- Add valid task into queue (Async)
- Dispatch task to worker
- Automatic check player's progress and submit remained achievements
- Query for task state
- Easy to expand for other visual novel task (See taskInterface.go)
 

## TODO
- use panic/recover to deal with AJAX Exception
- ability to stop task or worker
- ability to monitor worker health
- ability to assign specific type of task to specific set of workers
- more elegant way of task state update

## Licence
[GPLv3 Licence](https://en.wikipedia.org/wiki/GNU_General_Public_License#Version_3)