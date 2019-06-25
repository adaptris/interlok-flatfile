# interlok-flatfile
[![GitHub tag](https://img.shields.io/github/tag/adaptris/interlok-flatfile.svg)](https://github.com/adaptris/interlok-flatfile/tags) [![Build Status](https://travis-ci.org/adaptris/interlok-flatfile.svg?branch=develop)](https://travis-ci.org/adaptris/interlok-flatfile) [![CircleCI](https://circleci.com/gh/adaptris/interlok-flatfile/tree/develop.svg?style=svg)](https://circleci.com/gh/adaptris/interlok-flatfile/tree/develop) [![codecov](https://codecov.io/gh/adaptris/interlok-flatfile/branch/develop/graph/badge.svg)](https://codecov.io/gh/adaptris/interlok-flatfile) [![Total alerts](https://img.shields.io/lgtm/alerts/g/adaptris/interlok-flatfile.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/adaptris/interlok-flatfile/alerts/) [![Language grade: Java](https://img.shields.io/lgtm/grade/java/g/adaptris/interlok-flatfile.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/adaptris/interlok-flatfile/context:java)

As part of the 3.9.0 release, we decided to move flatfile support into its own package.

So here it is, if you were looking for it, then you can still depend on it via gradle/ivy/maven as usual.

```
compile ("com.adaptris:interlok-flatfile:3.9-SNAPSHOT") { changing= true}
```

```
<dependency org="com.adaptris" name="interlok-flatfile" rev="3.9-SNAPSHOT" conf="runtime->default" changing="true"/>
```

```
<dependency>
  <groupId>com.adaptris</groupId>
  <artifactId>interlok-flatfile</artifactId>
  <version>3.9-SNAPSHOT</version>
</dependency>
```
