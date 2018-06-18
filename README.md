# scrape

Command line script that builds CSV results of job searches. Check
out the `jobs` folder some recent scrapes. Uses the power of [Mechanize](
https://github.com/sparklemotion/mechanize) and [OptionParser](
https://docs.ruby-lang.org/en/2.5.0/OptionParser.html).

Hey Wow :) looks like there are still jobs for [Cobol](
https://en.wikipedia.org/wiki/COBOL)

### Seek 

[https://www.seek.com.au/](https://www.seek.com.au/): 
Large Australian employment marketplace

```
$ ruby seek.rb -h
Usage: seek.rb [options]
    -k, --keyword keyword            Keywords to search
    -h, --help                       Displays help
```
Or to enter interactive mode
```
$ ruby seek.rb 
Enter keywords: github devops linux
15 jobs found
```
