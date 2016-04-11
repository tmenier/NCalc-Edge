# XCalc
An NCalc fork with a focus on extensibility

## What is NCalc?
[NCalc](https://ncalc.codeplex.com/) is a mathematical expressions evaluator for .NET.

## Why a(nother) fork?
I can appreciate that too many forks can be confusing to the community, so I want to be very clear with my intent.

First, a little history. NCalc has gone unchanged for several years. The orginal author now works on Jint, another expression evaluator
which also happens to be a full-blown JavaScript interpreter. ([Check it out](https://github.com/sebastienros/jint), it's awesome.)

@pitermarx currently maintains 2 NCalc forks: [NCalc-Edge](https://github.com/pitermarx/NCalc-Edge), which contains some minor updates 
but remains true to the original and will never contain breaking changes. [NCalc2](https://github.com/pitermarx/NCalc2) is a work in 
progress though not active of late.

My fork arose out of a need for a modified NCalc at my day job. More than anything, we needed better extensibility hooks. Specifically,
we needed to be able to customize the behavior of the enigine at any node as it crawls the parsed expression tree. I believe these
and other modifications could be useful to the community, so I decided to re-brand my fork and make it available.

## What's next?
At this point I make no promises about maintaining backward compatibility with NCalc, but I will be sure to highlight those differences
here. Additonal documentation and NuGet packages coming soon.
