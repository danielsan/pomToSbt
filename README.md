# pomToSbt
Convert pom dependencies to what you can stuff into build.sbt.

Adapted from George Pligor's http://stackoverflow.com/questions/15430346/how-could-i-convert-a-pom-xml-to-sbt-dependencies great scala script, but this here is not a scala script but a plain scala program. I just found this adaptation more useful for my needs, and scala scripts are a pain to set up on your system.

Usage: place a _pom.xml_ in the root directory, then `sbt run`

Bug: my crude adaptation produces an extra comma at the end of the sbt dependencies sequence. Was never important enough to fix so far.

