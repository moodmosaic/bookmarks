# bookmarks
Contains a selection of the links I find interesting over time.

## Table of Contents

* [Haskell](#haskell)
 * [GHC](#ghc)
 * [Cabal](#cabal)
 * [Platforms](#platforms)
 * [Hackage](#hackage)
 * [Parsec](#parsec)
 * [QuickCheck](#quickcheck)
 * [Prettyprint](#prettyprint)
 * [Learning](#learning)
* [Scala](#scala)
 * [Conferences](#conferences)
 * [Learning](#learning-1)
* [F#](#f)
 * [Ionide](#ionide)
 * [FAKE](#fake)
 * [Prettyprint](#prettyprint-1)
 * [Learning](#learning-2)
* [.NET](#net)
 * [Interop](#interop)
 * [Learning](#learning-3)
 * [Platforms](#platforms-1)
* [Git](#git)
 * [Learning](#learning-4)
* [Cryptocurrencies](#cryptocurrencies)
 * [Price charts](#price-charts)
* [Category theory](#category-theory)
 * [Learning](#learning-5)
* [Leisure](#leisure)
 * [Life](#life)
 * [High fidelity](#high-fidelity)
 * [Furniture](#furniture)
 * [Juno Records](#juno-records)
 * [Tracklists](#tracklists)

## Haskell

### GHC

Haskell: Some Awesome Language Extensions Explained  
http://unbui.lt/#!/post/haskell-language-extensions/

GHCi's pretty-printer can be switched  
https://twitter.com/thumphriees/status/819783361614876672

The Glorious Glasgow Haskell Compilation System User's Guide, Version 7.10.3  
Warnings and sanity-checking  
https://downloads.haskell.org/~ghc/7.10.3/docs/html/users_guide/options-sanity.html

Submitting a pull request to GHC  
https://chris-martin.org/2017/phabricator-ghc-pull-request

### Cabal

*"Well, regarding the name, Cabal is indeed the library that all tools use, e.g. the .cabal file in a project. The bad name here is the build tool "cabal-install" because that has confused the hell out of everyone. There's three things here: a library called Cabal, a build tool called "Stack", and a build tool that should be called "some-haskell-build-tool" like maybe "haskbuilder" but is instead called "cabal-install" because it is some-build-tool-that-uses-the-Cabal-library (although that description works for Stack too). So the two tools with cabal in the name confuse everyone."*  
https://github.com/snowdriftcoop/snowdrift/pull/330#issuecomment-220034237

Protection against cabal swindling, robbing, injuring or sabotaging people with chopsticks  
https://github.com/ambiata/mafia

Build your Haskell project continuously  
https://kseo.github.io/posts/2017-01-28-build-your-haskell-project-continuously.html

QuickCheck in Test-suite type "detailed"  
https://www.schoolofhaskell.com/user/griba/quickCheck-in-test-suite-type-detailed

### Platforms

JavaScript vs Elm vs PureScript vs GHCjs (vs Scala.js)  
http://mutanatum.com/posts/2017-01-12-Browser-FP-Head-to-Head.html

HaskellPlatform-7.10.3-x86_64-setup  
https://downloads.haskell.org/~platform/7.10.3/HaskellPlatform-7.10.3-x86_64-setup.exe

Once the Haskell Platform is installed, do

```
cabal install hsdev
```

And it should then copy the following executables in the `bin` folder

```
01/17/2017  12:33 PM        10,316,288 aeson-pretty.exe
01/17/2017  12:32 PM         2,250,240 cpphs.exe
01/17/2017  12:34 PM        60,339,712 hdocs.exe
01/17/2017  12:36 PM        14,367,744 hlint.exe
01/17/2017  12:39 PM        82,327,552 hsautofix.exe
01/17/2017  12:39 PM        82,304,512 hscabal.exe
01/17/2017  12:39 PM        82,321,408 hsclearimports.exe
01/17/2017  12:39 PM        82,655,744 hsdev.exe
01/17/2017  12:39 PM        82,303,488 hshayoo.exe
01/17/2017  12:39 PM        82,310,656 hsinspect.exe
```

Once hsdev is installed, do

```
cabal install stylish-haskell
```

And it should then copy the following executables in the `bin` folder

```
01/17/2017  12:46 PM        10,061,824 json2yaml.exe
01/17/2017  12:47 PM        18,455,040 stylish-haskell.exe
01/17/2017  12:46 PM         9,517,056 yaml2json.exe
```

After that, use Stack for everything else.

stack-1.3.2-windows-x86_64-installer  
https://github.com/commercialhaskell/stack/releases/download/v1.3.2/stack-1.3.2-windows-x86_64-installer.exe

### Hackage

Reverse Dependencies - You choose a package and it tells you its reverse dependencies: those packages that depend upon it. It also tells you which packages are incompatible with the current version of the package  
http://packdeps.haskellers.com/reverse

### Parsec

An introduction to parsing text in Haskell with Parsec  
http://unbui.lt/#!/post/haskell-parsec-basics

Real World Haskell - Chapter 16. Using Parsec  
http://book.realworldhaskell.org/read/using-parsec.html

Parsec, a fast combinator parser  
https://research.microsoft.com/en-us/um/people/daan/download/parsec/parsec.pdf

An Introduction to the Parsec Library  
https://kunigami.blog/2014/01/21/an-introduction-to-the-parsec-library/

Impact on style of GHC -Wall (re-learned to write parsers in Applicative style)  
http://stackoverflow.com/a/4176570/467754

Intro to Parsing with Parsec in Haskell  
http://jakewheat.github.io/intro_to_parsing/

A nice example of using parsec to parse XML files  
https://static.charlieharvey.org.uk/writings/ReadXML.hs.txt

### QuickCheck

Lights are flashing, cars are crashing, getting frequent now - A small library of useful quickcheck generators, laws and other bits and pieces  
https://github.com/ambiata/disorder.hs

### Prettyprint

hfmt - A tool for formatting Haskell programs. Currently it is simply a gofmt style wrapper of the excellent tools hlint, hindent, and stylish-haskell  
https://github.com/danstiner/hfmt

### Learning

Lined-up Haskell types  
https://chris-martin.github.io/haskell-aligned/

CSCI 360: Programming Languages (Fall 2016)  
http://ozark.hendrix.edu/~yorgey/360/f16/

The Curse of the Excluded Middle - "Mostly functional" programming does not work  
http://queue.acm.org/detail.cfm?id=2611829

How much space does an 8-bit integer occupy in C and Haskell?  
https://ro-che.info/articles/2017-01-25-word8-space

This guy wrote the TCP state transitions in #Haskell with the hope that he would remember them better ... might have worked:  
https://gist.github.com/jfischoff/924c6608bc3284a72112ee4e13645a82

Haskell Bits #1: Randomness  
http://www.kovach.me/posts/2017-01-30-haskell-bits-randomness.html

Haskell Bits #2: Application Beginnings  
http://www.kovach.me/posts/2017-02-03-haskell-bits-application-beginnings.html

Haskell Bits #3: Connecting to Databases  
http://www.kovach.me/posts/2017-02-08-connecting-to-databases.html

Haskell Bits #4: Environment Variables  
http://www.kovach.me/posts/2017-02-22-environment-variables.html

How to make illegal values unrepresentable?  
http://stackoverflow.com/questions/42341535/how-to-make-illegal-values-unrepresentable

(A simple) REST API in Haskell  
http://maciek.io/rest-api-in-haskell/

## Scala

### Conferences

Scala Days  
http://scaladays.org/

### Learning

Asynchronous Programming and Scala, via @alexelcu  
https://alexn.org/blog/2017/01/30/asynchronous-programming-scala.html

## F# ##

### Ionide

Expecto test-runner in Ionide (integration point)  
https://github.com/ionide/ionide-vscode-fsharp/blob/master/src/Components/Expecto.fs

Create an F# project in Visual Studio Code  
https://codurance.com/2017/01/26/create-an-fsharp-project-in-vscode/

### Fake

Specifying FAKE targets  
http://www.davesquared.net/2017/02/fake-targets.html

### Prettyprint

fantomas - F# source code formatter, inspired by scalariform for Scala, ocp-indent for OCaml and PythonTidy for Python  
https://github.com/dungpa/fantomas

### Learning

The Gamma - Experiments in tooling for data-driven storytelling  
https://github.com/the-gamma

Free monads - A terrible way of separating pure and impure code  
http://stackoverflow.com/questions/41667721/free-monad-in-f-with-generic-output-type#comment70551788_41668459

Tour of F#  
https://docs.microsoft.com/en-us/dotnet/articles/fsharp/tour

## .NET

### Learning

docs.microsoft.com is Microsoft's new unified technical documentation experience  
https://docs.microsoft.com/en-us/

The .NET Language Strategy  
https://blogs.msdn.microsoft.com/dotnet/2017/02/01/the-net-language-strategy/

### Platforms

**Warning: This section probably needs cleanup.**

If I don't want to install Microsoft Visual Studio, then which SDK, Runtime, Targeting Pack do I have to install?  
http://getdotnet.azurewebsites.net/target-dotnet-platforms.html

How .NET Standard relates to .NET Platforms?  
https://gist.github.com/davidfowl/8939f305567e1755412d6dc0b8baf1b7

Working with Multiple .NET Core SDKs - both project.json and msbuild/csproj  
http://www.hanselman.com/blog/WorkingWithMultipleNETCoreSDKsBothProjectjsonAndMsbuildcsproj.aspx

This repo contains the .NET Core runtime, called CoreCLR, and the base library, called mscorlib. It includes the garbage collector, JIT compiler, base .NET data types and many low-level classes.  
https://github.com/dotnet/coreclr

The Book of the Runtime (BOTR) for the .NET Runtime  
https://github.com/dotnet/coreclr/blob/master/Documentation/botr/README.md

dotnet new angular and dotnet new react  
https://www.hanselman.com/blog/dotnetNewAngularAndDotnetNewReact.aspx

@DamianEdwards NDC London talk w/ @davidfowl on #aspnetcore patterns & anti-patterns  
https://vimeo.com/204080268

OpenID Connect from ASP.NET Core - on Mac OSX  
https://grean.com/easyid/aspnetcore/oidc/2017/02/25/aspnet-core-and-easyid.html

WordPress Running on .NET Core  
http://www.peachpie.io/2017/02/wordpress-announcement.html

F# and .NET Core SDK working together  
https://github.com/dotnet/netcorecli-fsc

.NET Core landing page  
https://docs.microsoft.com/en-us/dotnet/articles/core/

### Interop

Creating .NET Bindings for C Libraries with ObjectiveSharpie  
http://tirania.org/blog/archive/2017/Jan-18.html

## Git

### Learning

Use git add --patch for better commit history and mitigating bugs  
https://egghead.io/lessons/tools-use-git-add-patch-for-better-commit-history-and-mitigating-bugs

## Cryptocurrencies

### Price charts

Live price charts and market data for Bitcoin, Ethereum, and more  
https://cryptowat.ch/

## Category theory

### Learning

What is Category Theory Anyway?  
http://www.math3ma.com/mathema/2017/1/17/what-is-category-theory-anyway

## Leisure

### Life

Why Time Flies - Maximilian Kiener  
http://www.maximiliankiener.com/digitalprojects/time/

How to organize a meetup  
http://www.jefclaes.be/2017/02/how-to-organize-meetup.html

### High fidelity

Dynamic Range Database  
http://dr.loudness-war.info/

### Furniture

Hoerboard – Pro Audio & DJ Furniture | The Customized DJ Table  
http://www.hoerboard.com/furniture/nineteen/

### Juno Records

*(Latest checked)*

RAHAAN / TED EMPLETON  
Dessert Island Discs (180 gram vinyl 12")  
Dessert Island Discs  
Cat: DID 017  
01 Jan 17  
Disco / Nu-Disco

### Tracklists

'We Love' Desyn Masiello live set archive  
http://www.inthemix.com.au/forum/showthread.php?t=152076

