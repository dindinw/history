
# Go0 History

- Go0 Code timeline 

| Version        | Note                                               | Imp  |
| -------------- | -------------------------------------------------- | ---- |
| go0.2008-03-04 | doc: gri's first spec.                             |      |
| go0.2008-03-28 | src/c: ken's initial compiler code.                | `*`  |  
| go0.2008-05-08 | src/c: more ken's code.                            |      | 
| -------------- | -------------------------------------------------  |      |
| go0.2008-06-05 | 6g/6l: rob first import complate compiler code.    |      |
| go0.2008-06-06 | test/ken: rob add ken's test.                      |      |
| go0.2008-06-08 | test: rob update a lot tests and refactor.         |      | 
| go0.2008-06-12 | 6g/6l: rob add miss headers. (include)             | `**` | 
| -------------- | -------------------------------------------------  |      |
| go0.2008-08-05 | the latest version before scheduler change         | `**` |  
| go0.2008-08-06 | runtime/proc: rsc's new scheduler                  | `***`|
| go0.2008-09-10 | rob's frist-tutorial                               | `*`  |
| -------------- | -------------------------------------------------  | ---- |
| go0.2009-02-19 | the last txt file `doc/go_spec.txt`                |      |
| go0.2009-05-24 | build: rsc remove all compat.h                     | `?`  |
| go0.2009-10-07 | cmd/ld: rsc refactor 5l/6l/8l into ld              | `**` | 
| go0.2009-11-06 | the oldest tag exist in offical go repository      | `*`  |
| ---------------| -------------------------------------------------  |      |     
| go0.r56 (2011/03/16)| ||
| go0.r57 (2011/05/03)| ||
| go0.r58 (2011/06/29)| ||
| go0.r58.2           | ||
| go0.r59 (2011/08/01)| ||
| go0.r60 (2011/09/07)| ||
| ------------------- | -------------------------------------------------  ||
| go0.weekly.2011-10-06 | first standalone go (design) (rsc 09/29/11)     |`*`|
| go0.weekly.2011-12-14 | first standalone go (almost) (rsc ...)          ||
| go0.2012-01-30        | rob's standalone go                             ||
| go0.weekly.2012-02-07 | standalone go already (6g/6l move to bin/tools) |`**`|
| go0.weekly.2012-02-22 | ||
| go0.weekly.2012-03-04 | almost go1||
| go1 (2012.03.28)      | ||


- Some go0 note extracted from `How Go was made` (2015)
  + https://talks.golang.org/2015/how-go-was-made.slide#9
    - by Andrew Gerrand, (GopherCon15 Closing Keynote, 9 July 2015)
    - 1. last svn 777ee (July 2008)
      - https://github.com/golang/go/tree/777ee7163bba96f2c9b3dfe135d8ad4ab837c062 (rob, Jul 21, 2008 )
      ```
      Subversion was the project's first version control system. (no code review!)
      The trio made 400 commits to Subversion.
      
      The last Subversion commit (git hash 777ee7, 21 July 2008) contained:
      
      - the spec,
      - a Go compiler (linux/darwin amd64),
      - a few packages (fmt, rand, and math),
      - some test programs.
      ```
    - 2. perforce (Aug/Sep 2008)
      ```
      In July 2008 the project migrated from Subversion to Perforce,

      to use Google's excellent code review system.
      
      The team grew:
      
      Russ Cox joined in August 2008,
      Ian Lance Taylor joined in September,
      ~20 other Googlers got involved in their 20% time.
      ```
    -  3. 10 November 2009: Go was released. (78c47c3)
      - https://github.com/golang/go/tree/78c47c36b2984058c1bec0bd72e0b127b24fcd44 (rsc, Nov 10, 2009)
  
- Go0 Specs
  + [design/go0spec0](https://github.com/golang/go/blob/e6626dafa8de8a0efae351e85cf96f0c683e0a4f/doc/go_lang.txt) The Go Programming Language. Language Specification (March 7, 2008) intial version. add `iota`. 
  + [design/go0spec1](https://github.com/golang/go/blob/cb87526ce3531557ccf69969de4c8018956b10b5/doc/go_lang.txt) The Go Programming Language. Language Specification (March 28, 2008) add `select`. 
  + [design/go0spec2]() (Apr 17/18/29 2008) `.()` notion & type conversion
  + [design/go0sepc3]() (May 5/8/14 2008) forward declaration of types
  + [design/go0sepc4]() (Jun 6/9/12 2008) omitted variable type 
  + []() (Jul 1/3/7/8/16/21/22 2008)
  + []() (Aug 4/7/11/12/20/21/28/29 2008)
  + []() (Sep 3/4/8/9/10/11/12/17/19/26/27/29/30 2008)
  + []() (Oct 1/2/3/7/8/9/10/15/20/23/24/28/30 2008)
  + []() (Nov 3/4/7/13/17 2008)
  + []() (Dec 4/12/16/17/18 2008)
  + []() (Jan 5/6/7/16/23/*26*/27/30 2009) defer
  + []() (Feb 5/6/*11*/25 2009) unsafe 
  + []() (Mar 25 2010) 
  + []() (May 4/7/14/24/26 2010) 
  + []() (Jun 1/7/12/14/29 2010) 
  + []() (Sep 1/2/7/24/27/28 2010) 
  + []() (Oct 21/25/26/27/29 2010) 
  + []() (Nov 4 2010) 
  + []() (Dec 2 2010) 
  + []() (Jan 7/13/18/26/27 2011) 
  + []() (Feb 1/3/4/8/15/19/22 2011) 
  + []() (Mar 3/7/11/15/28 2011) 
  + []() (Apr 5/19/22/29 2011) 29 is revert 
  + []() (May 2/4/12/13/15/23/24 2011) 
  + []() (Jun 7/10/13 2011) 
  + []() (Jul 14 2011) 
  + []() (Aug 31 2011) 
  + []() (Sep 29 2011) 
  + []() (Oct 13/17/25 2011) 
  + []() (Nov 1/9/13/14/22 2011)
  + []() (Dec 2/5/8/10/12/13/14/15 2011)
  + []() (Jan 9/13/21/30/ 2012) go1
  + []() (Feb 6/8/13/14/16/21/22/23/28/29 2012) 
  + [design/go1spec]() (Mar 1/7/12/*17* 2012)  go1 release (2012/03/28)

