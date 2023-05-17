# interlok-flatfile

[![GitHub tag](https://img.shields.io/github/tag/adaptris/interlok-flatfile.svg)](https://github.com/adaptris/interlok-flatfile/tags)
[![license](https://img.shields.io/github/license/adaptris/interlok-flatfile.svg)](https://github.com/adaptris/interlok-flatfile/blob/develop/LICENSE)
[![Actions Status](https://github.com/adaptris/interlok-flatfile/actions/workflows/gradle-publish.yml/badge.svg)](https://github.com/adaptris/interlok-flatfile/actions)
[![codecov](https://codecov.io/gh/adaptris/interlok-flatfile/branch/develop/graph/badge.svg)](https://codecov.io/gh/adaptris/interlok-flatfile)
[![CodeQL](https://github.com/adaptris/interlok-flatfile/workflows/CodeQL/badge.svg)](https://github.com/adaptris/interlok-flatfile/security/code-scanning)
[![Known Vulnerabilities](https://snyk.io/test/github/adaptris/interlok-flatfile/badge.svg?targetFile=build.gradle)](https://snyk.io/test/github/adaptris/interlok-flatfile?targetFile=build.gradle)
[![Closed PRs](https://img.shields.io/github/issues-pr-closed/adaptris/interlok-flatfile)](https://github.com/adaptris/interlok-flatfile/pulls?q=is%3Apr+is%3Aclosed)

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
