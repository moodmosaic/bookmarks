# bookmarks
A selection of the links I find interesting over time.

## Table of Contents

* [C](#c)
* [Haskell](#haskell)
* [Category theory](#category-theory)
* [F#](#f)
* [.NET](#net)
* [Git](#git)
* [Unix-like](#unix-like)
* [Cryptocurrencies](#cryptocurrencies)
* [Leisure](#leisure)

## C

The Descent to C, by Simon Tatham  
https://www.chiark.greenend.org.uk/~sgtatham/

Property-based testing for C: generate input to find obscure bugs, then reduce to minimal failing input  
https://github.com/silentbicycle/theft

Throw The Switch - C Code That Doesn't Suck  
https://github.com/ThrowTheSwitch  

Embedded Testing with Unity and CMock  
http://www.lulu.com/shop/mark-vandervoord/embedded-testing-with-unity-and-cmock/paperback/product-14408590.html  

C/C++ for Visual Studio Code  
https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools  

## Haskell

BFPG talk series based on the CIS194 lecture series  
https://github.com/bfpg/cis194-yorgey-lectures

Haddock Markup Quick Reference  
https://github.com/ghc/haddock/tree/master/doc/cheatsheet
https://gist.github.com/bsmt/d9d3b1d94f3dc492955667dd52847ad5

Safe Haskell  
https://downloads.haskell.org/~ghc/8.2.2/docs/html/users_guide/safe_haskell.html

haskell-vim - Syntax Highlighting and Indentation for Haskell and Cabal  
https://github.com/neovimhaskell/haskell-vim

Haskell Development with Neovim  
https://blog.jez.io/haskell-development-with-neovim/

config-value - A simple, layout-based value definition language used for supplying configuration values to various applications  
https://github.com/glguy/config-value

Validation - Several data-types like Either but with differing properties and type-class instances  
https://github.com/tonymorris/validation

MTL style for free  
http://h2.jaguarpaw.co.uk/posts/mtl-style-for-free/

Cheatsheet: Stacking the State and Either Monads  
http://jeremymikkola.com/posts/2018_04_02_cheatsheet_state_and_error.html

Haskell: Some Awesome Language Extensions Explained  
http://unbui.lt/#!/post/haskell-language-extensions/

GHCi's pretty-printer can be switched  
https://twitter.com/thumphriees/status/819783361614876672

The Glorious Glasgow Haskell Compilation System User's Guide, Version 7.10.3  
Warnings and sanity-checking  
https://downloads.haskell.org/~ghc/7.10.3/docs/html/users_guide/options-sanity.html

The Glorious Glasgow Haskell Compilation System User's Guide, Version 8.0.1  
Warnings and sanity-checking  
https://downloads.haskell.org/~ghc/8.0.1/docs/html/users_guide/using-warnings.html#options-sanity

Submitting a pull request to GHC  
https://chris-martin.org/2017/phabricator-ghc-pull-request

*"Well, regarding the name, Cabal is indeed the library that all tools use, e.g. the .cabal file in a project. The bad name here is the build tool "cabal-install" because that has confused the hell out of everyone. There's three things here: a library called Cabal, a build tool called "Stack", and a build tool that should be called "some-haskell-build-tool" like maybe "haskbuilder" but is instead called "cabal-install" because it is some-build-tool-that-uses-the-Cabal-library (although that description works for Stack too). So the two tools with cabal in the name confuse everyone."*  
https://github.com/snowdriftcoop/snowdrift/pull/330#issuecomment-220034237

Protection against cabal swindling, robbing, injuring or sabotaging people with chopsticks  
https://github.com/ambiata/mafia

Stackage-Everything generator  
https://github.com/quchen/stackage-everything

Build your Haskell project continuously  
https://kseo.github.io/posts/2017-01-28-build-your-haskell-project-continuously.html

QuickCheck in Test-suite type "detailed"  
https://www.schoolofhaskell.com/user/griba/quickCheck-in-test-suite-type-detailed

Introduction to Nix (for users of Stack)  
https://chris-martin.org/2017/nix-for-stack-users

Which package version do I have?  
https://stackoverflow.com/q/33914073/467754

An opinionated guide to Haskell in 2018  
https://lexi-lambda.github.io/blog/2018/02/10/an-opinionated-guide-to-haskell-in-2018/

JavaScript vs Elm vs PureScript vs GHCjs (vs Scala.js)  
http://mutanatum.com/posts/2017-01-12-Browser-FP-Head-to-Head.html

[Elm](http://elm-lang.org) codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) spec and API  
https://github.com/rtfeldman/elm-spa-example
https://dev.to/rtfeldman/tour-of-an-open-source-elm-spa

Deploying Haskell on AWS Lambda  
http://engineers.irisconnect.net/posts/2017-03-16-deploying-haskell-on-aws-lambda.html

Experimental mobile haskell hackage overlay  
http://hackage.mobilehaskell.org/

Reverse Dependencies - You choose a package and it tells you its reverse dependencies: those packages that depend upon it. It also tells you which packages are incompatible with the current version of the package  
http://packdeps.haskellers.com/reverse

Haskell Tools  
http://haskelltools.com/

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

xleb - A simple monadic language for parsing XML structures  
https://github.com/aisamanra/xleb

Lights are flashing, cars are crashing, getting frequent now - A small library of useful quickcheck generators, laws and other bits and pieces  
https://github.com/ambiata/disorder.hs

kolmodin/binary/tests/Action.hs  
https://github.com/kolmodin/binary/blob/master/tests/Action.hs

Erlang Factory SF 2016 - Thomas Arts - Testing Asynchronous APIs With QuickCheck  
https://www.youtube.com/watch?v=iW2J7Of8jsE&feature=youtu.be&t=16m10s

Jacob Stanley - YOW! Lambda Jam 2017 Sydney - Gens N' Roses: Appetite for Reduction    
http://lambdajam.yowconference.com.au/speakers/jacob-stanley-2/
http://lambdajam.yowconference.com.au/slides/yowlambdajam2017/Stanley-GensNRoses.pdf

State machine testing with Hedgehog  
http://teh.id.au/posts/2017/07/15/state-machine-testing/index.html  
https://gist.github.com/thumphries/2e68275819e05a0d5e27ecb5dcd85dce

Moving Beyond Types (I wrote a bit about why starting from types is the wrong API for property-based testing)  
https://twitter.com/DRMacIver/status/886863724103032832/  
http://hypothesis.works/articles/types-and-properties/

hfmt - A tool for formatting Haskell programs. Currently it is simply a gofmt style wrapper of the excellent tools hlint, hindent, and stylish-haskell  
https://github.com/danstiner/hfmt

Haskell foreign import stdcall on DLL function  
http://stackoverflow.com/questions/1027246/haskell-foreign-import-stdcall-on-dll-function

How to Architect Medium to Large-Scale Haskell Applications  
https://skillsmatter.com/skillscasts/10832-how-to-architect-medium-to-large-scale-haskell-applications

FizzBuzz without modulo  
https://twitter.com/thelastinstance/status/972045314851995649

Get timings in GHCi  
https://stackoverflow.com/questions/10342217/get-timings-in-ghci/

Creating a GUI application in Haskell  
https://www.stackbuilders.com/tutorials/haskell/gui-application/

HTagLib - Haskell bindings for TagLib, an audio meta-data library  
https://github.com/mrkkrp/htaglib

Mark Karpov's OSS (FLAC, LAME, etc)  
https://markkarpov.com/oss.html

Screencasts focused on practical Haskell programming  
https://haskell-at-work.com/

A practitioner’s guide to reading programming languages papers  
https://blog.acolyer.org/2018/01/26/a-practitioners-guide-to-reading-programming-languages-papers/

Effectful Haskell: IO, Monads, Functors (by Stuart Popejoy who wrote [Pact](https://github.com/kadena-io/pact))    
http://slpopejoy.github.io/posts/Effectful01.html

Reading Simple Haskell  
https://soupi.github.io/rfc/reading_simple_haskell/

Haskell by Example  
http://lotz84.github.io/haskellbyexample/

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

Super Simple Scotty Site  
https://github.com/arcticmatt/happy-site

Retrieve bitcoin price index from coindesk  
https://github.com/lashtear/coindesk-bpi

Relationship between fmap and bind  
https://stackoverflow.com/questions/44105493/relationship-between-fmap-and-bind/44105828#44105828

selda: Type-safe, high-level EDSL for interacting with relational databases  
https://hackage.haskell.org/package/selda

How to make illegal values unrepresentable?  
http://stackoverflow.com/questions/42341535/how-to-make-illegal-values-unrepresentable

A Gentle Introduction to Monad Transformers or, Values as Exceptions  
https://github.com/kqr/gists/blob/master/articles/gentle-introduction-monad-transformers.md

kqr/gists/articles/simple-syntax-of-haskell.hs  
https://github.com/kqr/gists/blob/master/articles/simple-syntax-of-haskell.hs

Constrained checkboxes. How would you implement? - In @elmlang you maintain invariants with data structures!  
*Didn't know where to put this?! Need to cleanup my bookmarks at this point.*  
https://twitter.com/czaplic/status/859065124006445056

One of those situations where Haskell knowledge is applied elsewhere—A monadic parser for JSON written in JavaScript (using Free Monads)  
https://www.reddit.com/r/haskell/comments/68nspj/a_jsonstream_parser_in_750_bytes_thanks_free/

Can't see the four-est for the trees  
http://gigamonkeys.com/trees/

Continuations From the Ground Up  
http://blog.ielliott.io/continuations-from-the-ground-up/

This is a pretty sweet-looking static site generator, straightforward Haskell makes me happy  
https://github.com/ChrisPenner/SitePipe

Modern FP with mtl  
https://gist.github.com/ocharles/6b1b9440b3513a5e225e

"[..] we can get the signature of foldr by reversing the arrows of unfoldr, and vice versa."  
https://kseo.github.io/posts/2016-12-12-unfold-and-fold.html

chrisdone/wish - A trivial web browser written in Haskell  
https://github.com/chrisdone/wish

How do I modify a variable in Haskell?  
http://www.michaelburge.us/2017/08/15/how-do-i-modify-a-variable-in-haskell.html

Roll your Own Bitcoin Exchange in Haskell  
http://www.michaelburge.us/2017/08/31/roll-your-own-bitcoin-exchange.html

tfausak/grawlix - Comment on Haskell documentation  
https://github.com/tfausak/grawlix
https://grawlix.herokuapp.com/

Monoids talk  
https://docs.google.com/presentation/d/1_sD9a5-u3urGbJPuxebBQXrDtoqvKlEII3brnm0ZWb0

Monoidal Parsing - Edward Kmett  
https://www.youtube.com/watch?v=Txf7swrcLYs

What does Free buy us?  
http://www.parsonsmatt.org/2017/09/22/what_does_free_buy_us.html

What is the Store comonad?  
https://stackoverflow.com/questions/8766246/what-is-the-store-comonad

Introduction to golden testing  
https://ro-che.info/articles/2017-12-04-golden-tests

Deploying Haskell Programs  
http://fosskers.ca/blog/deploying-haskell-en.html

Haskell-At-Work  
https://haskell-at-work.com/

Workthrough: Category Theory for Programmers (Milewski)  
https://www.johnchandlerburnham.com/posts/workthrough-category-theory-milewski.html

Workthrough: Tutorial Intro to Lambda Calculus (Rojas)  
https://www.johnchandlerburnham.com/posts/workthrough-lambda-calculus-rojas.html

Workthrough: Haskell Programming (Allen & Moronuki)  
https://www.johnchandlerburnham.com/posts/workthrough-hpfp.html

Are these two packages related?  
https://hackage.haskell.org/package/inspection-testing
https://github.com/ocharles/assert-explainer

OOPH: Data Inheritance  
http://www.parsonsmatt.org/2017/02/17/ooph_data_inheritance.html

## Category theory

Bartosz Milewski's Category Theory for Programmers  
https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/
https://github.com/hmemcpy/milewski-ctfp-pdf

From design patterns to category theory  
http://blog.ploeh.dk/2017/10/04/from-design-patterns-to-category-theory/
https://cleancoders.com/videos/humane-code-real

Jan-Willem Buurlage's Notes on Category Theory and Haskell  
https://github.com/jwbuurlage/category-theory-programmers/

What is Category Theory Anyway?  
http://www.math3ma.com/mathema/2017/1/17/what-is-category-theory-anyway

## F# ##

Q: How can I work with F# in Visual Studio 2017 Version 15.3?

A: You should use nightly build of Visual F# Tool as described [here](https://blogs.msdn.microsoft.com/dotnet/2017/03/14/announcing-nightly-releases-for-the-visual-f-tools/):

> 1. Open Tools -> Extensions and Updates.
> 2. Click "Change your Extensions and Updates settings" on the bottom-left corner.
> 3. Click "Add" under "Additional Extension Galleries".
> 4. Under "Name", enter anything you like. Under "URL", enter https://dotnet.myget.org/F/fsharp/vsix
> 5. Click "Apply".
> 6. Click "OK".
>  
> It may take a few minutes for VS to refresh the feed, depending on your machine. Once that has happened, you can open Tools -> Extensions and Updates and notice that there is an update to the Visual F# tools!
https://stackoverflow.com/a/45709605/467754

Rezoom.SQL statically typechecks a common SQL dialect and translates it to various RDBMS backends  
https://github.com/rspeele/Rezoom.SQL

Expecto test-runner in Ionide (integration point)  
https://github.com/ionide/ionide-vscode-fsharp/blob/master/src/Components/Expecto.fs

Create an F# project in Visual Studio Code  
https://codurance.com/2017/01/26/create-an-fsharp-project-in-vscode/

Using VS Code for F# development? Collection of helpful tips and tricks for VS Code  
https://github.com/Microsoft/vscode-tips-and-tricks

Specifying FAKE targets  
http://www.davesquared.net/2017/02/fake-targets.html

Going Down the Property Based Testing Rabbit Hole  
http://blog.mavnn.co.uk/going-down-the-property-based-testing-rabbit-hole/

fantomas - F# source code formatter, inspired by scalariform for Scala, ocp-indent for OCaml and PythonTidy for Python  
https://github.com/dungpa/fantomas

F# language evolution  
https://en.wikipedia.org/wiki/F_Sharp_(programming_language)#Versions

Notes and Guidance on FSharp.Core  
https://fsharp.github.io/2015/04/18/fsharp-core-notes.html

The Gamma - Experiments in tooling for data-driven storytelling  
https://github.com/the-gamma

Free monads - A terrible way of separating pure and impure code  
http://stackoverflow.com/questions/41667721/free-monad-in-f-with-generic-output-type#comment70551788_41668459

Tour of F#  
https://docs.microsoft.com/en-us/dotnet/articles/fsharp/tour

Why 'object-programming' (see Twitter link below) matters in F#  
https://eiriktsarpalis.wordpress.com/2017/03/20/why-oo-matters-in-f/

Why object-programming matters in F# (Twitter discussion)  
https://twitter.com/dsyme/status/843849405212098560

A reusable ApiController Adapter  
http://blog.ploeh.dk/2017/03/30/a-reusable-apicontroller-adapter/

A reusable ApiController Adapter (GitHub issue)  
https://github.com/ploeh/ploeh.github.com/issues/276

Fixing Real Life Problems from the Ivory Tower - Audience Level: Advanced  
https://skillsmatter.com/skillscasts/9883-fixing-real-life-problems-from-the-ivory-tower

Functional Track talks from NDC London 2017  
https://gist.github.com/swlaschin/7b9dfe7c41df9d1ac92a544117a934df

Domain Modeling Made Functional - Tackle Software Complexity with Domain-Driven Design and F# (Scott Wlaschin)  
https://pragprog.com/book/swdddf/domain-modeling-made-functional

Understanding Functional Programming  
https://leanpub.com/understandingfunctionalprogramming/

Question of the day for you all: If we revise FSharp.Core (in a backwards-compatible way), what additions should we make?  
https://twitter.com/dsyme/status/930489150050054144

(Nearly) Everything You Ever Wanted to Know About F# Active Patterns but were Afraid to Ask  
https://www.youtube.com/watch?v=AQ-8_8hfmGE

From Dependency Injection to Dependency Rejection  
https://youtu.be/2qxzDOHrdqs?t=14269

Encapsulation - C# vs F# vs Haskell, equivalent result  
http://blog.stermon.com/articles/2017/05/31/encapsulation-csharp-vs-fsharp-vs-haskell-equivalent-result

A great post on using F# type providers for database access on Linux  
https://twitter.com/dsyme/status/888121310420754432  
https://medium.com/@edgarsanchezg/accessing-a-relational-db-with-f-type-providers-7263d88aa640/

An end-to-end, functional-first stack for cloud-ready web development that emphasizes type-safe programming  
https://safe-stack.github.io/

How to transform OO calls into a some generic function calls  
https://stackoverflow.com/q/46792722/467754

F# how to pass equivalent of interface (Free Monad / `DoSomethingInstruction<'a>`)  
https://stackoverflow.com/a/45545737/467754

choice_vs_result.fs  
https://gist.github.com/vasily-kirichenko/b0cc41e6de8bdec2ce53072e87741e50

F# compiles down into (similar) IL code as VB and C#  
http://connelhooley.uk/blog/2017/04/30/f-sharp-to-c-sharp

## .NET

The history of C#  
https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-version-history#c-version-70
https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/

Tools built on top of CLRMD - that replace functionality of WinDBG  
https://gist.github.com/mattwarren/5f1be63ab0babd65b44a910b03abc474

C# language evolution  
https://github.com/dotnet/csharplang/blob/master/Language-Version-History.md
https://en.wikipedia.org/wiki/C_Sharp_(programming_language)#Versions

docs.microsoft.com is Microsoft's new unified technical documentation experience  
https://docs.microsoft.com/en-us/

.NET Application Architecture  
https://www.microsoft.com/net/learn/architecture

High-performance .NET by example: Filtering bot traffic (Was popular on Twitter)  
https://alexandrnikitin.github.io/blog/high-performance-dotnet-by-example/

The .NET Language Strategy  
https://blogs.msdn.microsoft.com/dotnet/2017/02/01/the-net-language-strategy/

Difference between decimal, float and double in .NET?  
https://stackoverflow.com/a/618596/467754

HTTPS on Stack Overflow: The End of a Long Road (don't know where else to put this one)  
https://nickcraver.com/blog/2017/05/22/https-on-stack-overflow/

Moving Past the Scaling Myth (Michael Feathers) (don't know where else to put this one either)  
https://www.infoq.com/presentations/scalability-variant-structuring

Deep-dive into .NET Core primitives: deps.json, runtimeconfig.json, and dll's  
http://www.natemcmaster.com/blog/2017/12/21/netcore-primitives/

If I don't want to install Microsoft Visual Studio, then which SDK, Runtime, Targeting Pack do I have to install?  
http://getdotnet.azurewebsites.net/target-dotnet-platforms.html

How .NET Standard relates to .NET Platforms?  
https://gist.github.com/davidfowl/8939f305567e1755412d6dc0b8baf1b7

Very cool video on the history of .NET and .NET Standard  
https://channel9.msdn.com/events/Connect/2017/E116

.NET Standard 2.0 is final  
https://github.com/dotnet/announcements/issues/24

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

ILLink (a .NET Core build of the mono linker) now ships with .NET Core and trims non-public unreachable IL and metadata  
https://github.com/dotnet/corefx/pull/17825

F# and .NET Core SDK working together  
https://github.com/dotnet/netcorecli-fsc

Announcing Nightly Releases for the Visual F# Tools  
https://blogs.msdn.microsoft.com/dotnet/2017/03/14/announcing-nightly-releases-for-the-visual-f-tools/

dotnet-architecture/eShopOnContainers - Easy to get started sample reference microservice and container based application  
https://github.com/dotnet-architecture/eShopOnContainers

Who's actually using .net core in production?  
https://www.reddit.com/r/dotnet/comments/6m88q7/whos_actually_using_net_core_in_production/

Creating .NET Bindings for C Libraries with ObjectiveSharpie  
http://tirania.org/blog/archive/2017/Jan-18.html

Automating Windows Applications Using the WCF Equipped Injected Component  
https://www.codeproject.com/Articles/17924/Automating-Windows-Applications-Using-the-WCF-Equi

## Git

Flight rules for git - A guide for astronauts (now, programmers using git) about what to do when things go wrong  
https://github.com/k88hudson/git-flight-rules

Use git add --patch for better commit history and mitigating bugs  
https://egghead.io/lessons/tools-use-git-add-patch-for-better-commit-history-and-mitigating-bugs

Visualize how common Git operations affect the commit graph  
https://github.com/git-school/visualizing-git

Roadmap to becoming a web developer in 2017 (Git required for any path, so...)  
https://github.com/kamranahmedse/developer-roadmap

## Unix-like

Workshop on how to use Vim Plugins  
https://github.com/jez/vim-as-an-ide
https://blog.jez.io/haskell-development-with-neovim/

Oh My Zsh  
http://ohmyz.sh/

Nix: Under the hood by Gabriel Gonzalez  
https://www.youtube.com/watch?v=GMQPzv3Sx58

NixOS Linux  
https://nixos.org/

The Ultimate Vim Distribution  
http://vim.spf13.com/

Now color-coded! Two diagrams of the Unix architecture, 50 years apart. What they tell us and how I drew them.  
https://twitter.com/CoolSWEng/status/863090134232821761

fzf - A command-line fuzzy finder written in Go  
https://github.com/junegunn/fzf

iTerm2 - A replacement for Terminal and the successor to iTerm  
https://www.iterm2.com/

tmux - a "terminal multiplexer". It enables a number of terminals to be accessed and controlled from a single terminal.  
https://github.com/tmux/tmux

clustergit - run git commands on multiple git clones  
https://github.com/mnagel/clustergit

tonsky/FiraCode - Monospaced font with programming ligatures  
https://github.com/tonsky/FiraCode

Linux intro course - A gentle introduction to programming networked services on linux  
https://github.com/haf/linux-intro-course

Master the command line, in one page (in case I use neovim)  
https://github.com/jlevy/the-art-of-command-line  
https://pragprog.com/book/modvim/modern-vim  
https://github.com/ryanoasis/vim-devicons
https://github.com/tyrannicaltoucan/vim-quantum

Haskell Development with Neovim  
https://blog.jez.io/haskell-development-with-neovim/

Panic Inc - By request: here's a Terminal theme based on our official "Panic Palette". Enjoy!  
https://twitter.com/panic/status/558389225612005376

ShellProgressBar - display progress in your console application  
https://github.com/Mpdreamz/shellprogressbar

Terminal Spinner for .NET Core/Standard  
https://github.com/mayuki/Kurukuru

Why does man print “gimme gimme gimme” at 00:30?  
https://unix.stackexchange.com/questions/405783/why-does-man-print-gimme-gimme-gimme-at-0030

Pro MacBook Pro Tip: have a Touch Bar with Touch ID? If you edit /etc/pam.d/sudo and add the following line to the top  
https://twitter.com/cabel/status/931292107372838912

How to Run Linux Commands From Outside the Bash Shell on Windows 10  
https://github.com/moodmosaic/bookmarks.git

How do I mount shared folders in Ubuntu using VMware tools?  
https://askubuntu.com/a/41386

How do I install a .deb file via the command line?  
https://askubuntu.com/a/40781

ConEmu - Major changes since last Stable  
https://github.com/Maximus5/ConEmu/issues/1523

## Cryptocurrencies

My Crypto Guide - The Definitive Crypto guide for Beginners and Veterans Alike  
https://mycrypto.guide/

CCRG - The Cryptocurrency Research Group  
http://ccrg.org/

Why Haskellers should be interested in 'Smart Contracts'  
http://www.stephendiehl.com/posts/smart_contracts.html

About Ethereum  
https://consensys.net/ethereum/

Bitcoin: A Peer-to-Peer Electronic Cash System, Satoshi Nakamoto, October 31, 2008  
http://nakamotoinstitute.org/bitcoin/

Blockchain 101 - A Visual Demo  
https://anders.com/blockchain/

Programming The Blockchain in C#  
https://github.com/ProgrammingBlockchain

Thomas Dietert - Introduction to Cryptocurrencies in Haskell  
https://youtu.be/wjyiOXRuUdo
https://github.com/tdietert/nanocoin-pres

Adjoint Blog  
https://www.adjoint.io/posts.html

https://medium.com/hodl50/a-story-of-50-coins-de44826f4f47

Programming The Blockchain in C#  
https://programmingblockchain.gitbooks.io/programmingblockchain/

Best practices to help you store the top 50 cryptocurrencies  
https://hackernoon.com/a-story-of-50-coins-de44826f4f47

Live price charts and market data for Bitcoin, Ethereum, and more  
https://cryptowat.ch/

TradingView — free stock charts and quotes online  
https://www.tradingview.com/

Percentage of Total Market Capitalization (Dominance)  
https://coinmarketcap.com/charts/#dominance-percentage

Coinbase Index Fund  
https://am.coinbase.com/

## Leisure

Why Time Flies - Maximilian Kiener  
http://www.maximiliankiener.com/digitalprojects/time/

How to organize a meetup  
http://www.jefclaes.be/2017/02/how-to-organize-meetup.html

A great demonstration of why we need to plot the data and never trust statistics tables!  
https://www.autodeskresearch.com/publications/samestats

Roadmap to becoming a web developer in 2017  
https://github.com/kamranahmedse/developer-roadmap

The Internet Archive has digitized 25,000 78rpm Gramophone records  
http://great78.archive.org/preservation/
http://n-gate.com/

Dynamic Range Database  
http://dr.loudness-war.info/  
http://dynamicrange.de/

High Fidelity Phonograph Cartridge - Technical Seminar  
http://www.shure.com/americas/support/find-an-answer/high-fidelity-phonograph-cartridge-technical-seminar

Hoerboard – Pro Audio & DJ Furniture | The Customized DJ Table  
http://www.hoerboard.com/furniture/nineteen/

Juno Records  
*(Latest checked)*

PONTY MYTHON  
Pink Tango EP (hand-stamped 12")  
Futureboogie Recordings  
Cat: FBR 057. Rel: 19 Mar 18  
Pink Tango (5:52)  
Pink Tango (Fabrizio Mammarella remix) (7:17)  
Time Spiral (5:35)  
Appreciate It While It's Not Too Late (6:21)

'We Love' Desyn Masiello live set archive  
http://www.inthemix.com.au/forum/showthread.php?t=152076

LUKE FAIR dj sets by bringthebeats | Free Listening on SoundCloud  
https://soundcloud.com/bringthebeats/sets/luke-fair-dj-sets
