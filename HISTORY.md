# History

## 0.7.1

* improve default done regex to support both spigot and vanilla

## 0.7.0

* add OPTIONS parameter to specify the ram usage and the done string to check for spigot support

## 0.6.5

* go back to using mkdirp, which doesn't have any problem after all

## 0.6.4

* batch.concurrency(1) fixes the bug

## 0.6.3

* use fs.mkdir instead of mkdirp, should fix the bug

## 0.6.2

* fix the dir existence checking

## 0.6.1

* check the created path is actually created in wrap.js

## 0.6.0

* check with a md5 hash that the file downloaded is correct, doesn't download it if the destination file is already the correct file

## 0.5.4

* create empty banned-players.json, banned-ips.json, ops.json, whitelist.json to avoid errors

## 0.5.3

* fix writeServer

## 0.5.2

* don't stop the server if there's nothing to stop

## 0.5.1

* some cleanup of wrap

## 0.5.0

* change default properties to something more default

## 0.4.0

* add wrap.writeServer(line)

## 0.3.0

* separate stopping the server and deleting its files

## 0.2.0

* add downloadMinecraft to bin

## 0.1.0

* download and wrap functionality (mostly imported from mineflayer and node-minecraft-protocol)