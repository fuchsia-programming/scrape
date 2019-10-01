# **_scrape_**

[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=fuchsia-programming/scrape)](https://dependabot.com)
![GitHub last commit](https://img.shields.io/github/last-commit/fuchsia-programming/scrape)
![GitHub repo size](https://img.shields.io/github/repo-size/fuchsia-programming/scrape)
![GitHub language count](https://img.shields.io/github/languages/count/fuchsia-programming/scrape)
![GitHub top language](https://img.shields.io/github/languages/top/fuchsia-programming/scrape)
   
<img src="assets/images/logo.png" align="right">

## **When you need those jobs hypersonic...._scrape_**

**_scrape_** is a command line script that builds 🔧 🔩 🔨  
CSV results of job searches. Check out the [jobs](
https://github.com/fuchsia-programming/scrape/tree/master/jobs)
folder for some recent **_scrape_**_s_. 

**_scrape_** is built with:

- [Ruby](https://www.ruby-lang.org)
- [Mechanize](https://github.com/sparklemotion/mechanize)
- [OptionParser](https://docs.ruby-lang.org/en/2.5.0/OptionParser.html)
- [Rubocop](https://github.com/rubocop-hq/rubocop)
- [Paint](https://github.com/janlelis/paint)
- [RubyCritic](https://github.com/whitesmith/rubycritic)
- [Bundler](https://bundler.io/)
- [CSV class](https://ruby-doc.org/stdlib-2.5.0/libdoc/csv/rdoc/CSV.html)
- [XPath](https://en.wikipedia.org/wiki/XPath)
- [CSV](https://en.wikipedia.org/wiki/Comma-separated_values)
- [YAML](http://yaml.org/)
- [Markdown](https://daringfireball.net/projects/markdown/syntax)
- [GitHub Pages](https://pages.github.com/)
- [Jekyll](https://jekyllrb.com/)
- [Flag Counter](https://flagcounter.com)
- [GitHub Desktop](https://desktop.github.com/)
- [RubyMine](https://www.jetbrains.com/ruby/)
- [Terminal emulator](https://en.wikipedia.org/wiki/Terminal_emulator)
- [Jemoji](https://github.com/jekyll/jemoji)
- [The Cayman theme](https://github.com/pages-themes/cayman)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [PNG](https://en.wikipedia.org/wiki/Portable_Network_Graphics)

Hey Wow :) looks like there are still [jobs](https://github.com/fuchsia-programming/scrape/blob/master/jobs/cobol-worktype-all.csv) for [COBOL](
https://en.wikipedia.org/wiki/COBOL)

## Seek 

Large Australian employment marketplace
[https://www.seek.com.au/](https://www.seek.com.au/)  

```
$ ruby seek.rb -h
Usage: seek.rb [options]
    -k, --keyword keyword            Keywords to search
                                        separators include:
                                        and, or, not
    -l, --location location          Suburb, city or region
    -d, --daterange daterange        Listed time in days
                                        999 (default) or
                                        1, 3, 7, 14, 31 or
                                        any positive number
    -w, --worktype worktype          Work type
                                        all (default)
                                        full or 242 (full time)
                                        part or 243 (part time)
                                        contract or 244 (contract/temp)
                                        casual or 245 (casual/vacation)
    -h, --help                       Displays help
        --version                    Show version
```
Or to enter interactive mode
```
$ ruby seek.rb 
Enter keywords: git and python
Enter suburb, city or region: sydney
Listed time in days: 30
Work type: full
41 jobs found
```

Code overview of [seek.rb](
https://github.com/fuchsia-programming/scrape/blob/master/seek.rb) 
can be seen on the [RubyCritic page](
https://fuchsia-programming.github.io/scrape/rubycritic/overview.html).


## Tools

#### RubyCritic

RubyCritic is a Ruby gem that produces a web based report of the ruby
code in the project and is seen running below

```
$ rubycritic -p rubycritic/
```

#### Rubocop

Rubocop is a Ruby gem that is used to lint the projects Ruby code and
outputs a report in the terminal.

```
$ rubocop
```

<a href="https://info.flagcounter.com/0gCz">
    <img src="https://s05.flagcounter.com/count2/0gCz/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_250/viewers_0/labels_1/pageviews_0/flags_0/percent_0/" alt="Flag Counter">
</a>
