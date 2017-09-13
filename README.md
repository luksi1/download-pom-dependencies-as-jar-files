# download-jar-files-from-pom
Download .jar files that are dependencies in a pom.xml file

## Description

Parse a pom.xml file for dependencies and download the respective artifact and version from [the central repository](http://central.sonatype.org).

## Usage

```
./get-jar-files -f <MY POM.XML>
```

## Dependencies

#### Binaries
- Perl
- Wget

#### Perl modules
- Config::Augeas
- Getopts::Long (core module)
- Cwd (core module)

## Notes

Files are downloaded to your current working directory.

