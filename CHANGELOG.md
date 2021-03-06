# Changelog

## 0.13.0 (2016-11-29)

* remove unreachable code: monitor type cannot be "check" #72 (haya14busa)
* Fix the links to the api documents #73 (itchyny)
* catch up monitor interface changes of mackerel-client-go #74 (haya14busa)
* Introduce yudai/gojsondiff for `mkr monitors diff` #75 (haya14busa)
* fix test according to mackerel-client-go changes #76 (haya14busa)


## 0.12.0 (2016-10-27)

* Rename a dependent package #68 (usk81)
* Support `-apibase` option #69 (astj)
* [breaking change] Prepend `custom.` prefix to host metric name by default #70 (astj)


## 0.11.3 (2016-07-14)

* fix `validateRules()`,  when monitor has rule of "expression". #66 (daiksy)


## 0.11.2 (2016-06-23)

* replace angle brackets for json #63 (daiksy)


## 0.11.1 (2016-06-10)

* fix version number #61 (stanaka)


## 0.11.0 (2016-06-09)

* add dashboard generator #56 (daiksy)
* Add flag to overwrite host's roles  #58 (haya14busa)


## 0.10.1 (2016-05-25)

* fix signnatures. codegangsta/cli #54 (tknzk)


## 0.10.0 (2016-05-10)

* support `isMute` field of monitors #49 (Songmu)
* support boolean at isEmpty #51 (stanaka)
* bump up go version to 1.6.2 #52 (stanaka)


## 0.9.1 (2016-03-25)

* use GOARCH=amd64 for now #41 (Songmu)


## 0.9.0 (2016-02-18)

* Support displayName of host's json #39 (stanaka)


## 0.8.1 (2016-01-07)

* fix handling host-status option #37 (stanaka)


## 0.8.0 (2016-01-06)

* support alerts subcommand #31 (stanaka)
* Fix README example about mkr throw #32 (yuuki1)
* Build with Go 1.5 #33 (itchyny)
* Fixed the english used in the command descriptions #35 (stefafafan)


## 0.7.1 (2015-11-12)

* support `notificationIntervai` field in monitors (stanaka)
* [bug] fix json parameter s/hostID/hostId/g (Songmu)

## 0.7.0 (2015-10-26)

* append newline to the end of monitors.json #23 (Songmu)
* fix printMonitor #24 (Songmu)
* fix diff output between slices #25 (Songmu)

## 0.6.0 (2015-10-15)

* Fix update command bug about overwriting hostname #17 (y_uuki)
* Stop the parallel request sending temporarily #18 (y_uuki)
* Suppress to display empty fields when mkr monitors diff #20 (by stanaka)

## 0.5.0 (2015-09-14)

 * add fields for external URL monitors (stanaka)

## 0.4.1 (2015-08-28)

* Create deb/rpm package for Linux release #11 (Sixeight)


## 0.3.0 (2015-07-05)

* [feature] add --conf option to specify conf file path #4 (Sixeight)
* [fix] Fix update command as firstaid #7 (Sixeight)

## 0.2.0 (2015-06-18)

* [feature] add -f flag to hosts command to format the output #2 (motemen)
